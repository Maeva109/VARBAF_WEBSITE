<script lang="ts" setup>
const { href, variant, costumSpanClass="", costumTextColor="" } = defineProps<{
    href:string,
    variant:"primary"|"primary-outlined"|"secondary"|"secondary-outlined"|"costum"|"white",
    costumSpanClass?:string,
    costumTextColor?:string
}>()

let spanClass:string = "";
let textCl:string = ""
if (variant === "primary") {
    spanClass = "bg-primary border-2 border-transparent"
    textCl = "text-white"
}else if(variant === "primary-outlined"){
    spanClass = "border-2 border-primary"
    textCl = "text-primary"
}
else if(variant === "secondary"){
    spanClass = "bg-primary/5"
    textCl = "text-primary"
}
else if(variant === "costum"){
    spanClass=costumSpanClass
    textCl = costumTextColor
}
else if(variant === "white"){
    spanClass = "bg-white border-2 border-transparent"
    textCl = "text-primary"
}

</script>
<template>
    <NuxtLink
    :to="href"
    :class="[
        'relative overflow-hidden inline-flex items-center justify-center px-6 py-3 rounded-lg font-medium transition-colors duration-300',
        variant === 'primary' && 'bg-primary text-white hover:bg-primary-dark',
        variant === 'secondary' && 'bg-gray-200 text-gray-800 hover:bg-gray-300 dark:bg-gray-700 dark:text-white dark:hover:bg-gray-600',
        variant === 'white' && 'bg-white text-primary hover:bg-gray-100'
    ]"

>
        <span v-if="variant!=='costum'" class="absolute inset-0 rounded-full group-hover:scale-105 origin-center transition-all ease-in-out" :class="spanClass"></span>
        <span class="relative flex items-center justify-center" :class="textCl">
            <slot/>
        </span>
    </NuxtLink>
</template>