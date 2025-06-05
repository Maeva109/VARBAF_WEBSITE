<template>
  <div class="py-20">
    <div class="container mx-auto px-4">
      <h1 class="text-4xl font-bold text-center mb-12">Galerie Photos</h1>

      <!-- Filtres -->
      <div class="flex flex-wrap justify-center gap-4 mb-12">
        <button class="px-4 py-2 rounded-full bg-primary text-white hover:bg-primary-dark">
          Toutes les photos
        </button>
        <button class="px-4 py-2 rounded-full bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
          Architecture
        </button>
        <button class="px-4 py-2 rounded-full bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
          Produits
        </button>
        <button class="px-4 py-2 rounded-full bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
          Événements
        </button>
        <button class="px-4 py-2 rounded-full bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
          Artisans
        </button>
      </div>

      <!-- Grille de photos -->
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
        <!-- Photo 1 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery1.jpg" alt="Vue extérieure" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Vue extérieure
            </span>
          </div>
        </div>

        <!-- Photo 2 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery2.jpg" alt="Sculpture en bois" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Sculpture en bois
            </span>
          </div>
        </div>

        <!-- Photo 3 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery3.jpg" alt="Bronze" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Bronze
            </span>
          </div>
        </div>

        <!-- Photo 4 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery4.jpg" alt="Textile" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Textile
            </span>
          </div>
        </div>

        <!-- Photo 5 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery5.jpg" alt="Atelier" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Atelier
            </span>
          </div>
        </div>

        <!-- Photo 6 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery6.jpg" alt="Exposition" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Exposition
            </span>
          </div>
        </div>

        <!-- Photo 7 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery7.jpg" alt="Formation" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Formation
            </span>
          </div>
        </div>

        <!-- Photo 8 -->
        <div class="relative group cursor-pointer">
          <img src="/images/gallery8.jpg" alt="Événement" class="w-full h-64 object-cover rounded-lg">
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-50 transition-all duration-300 rounded-lg flex items-center justify-center">
            <span class="text-white opacity-0 group-hover:opacity-100 transition-opacity duration-300">
              Événement
            </span>
          </div>
        </div>
      </div>

      <!-- Bouton Voir plus -->
      <div class="text-center mt-12">
        <button class="px-6 py-3 bg-primary text-white rounded-lg hover:bg-primary-dark transition-colors duration-300">
          Voir plus de photos
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'default'
})
</script> 