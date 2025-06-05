<template>
  <div class="py-20">
    <div class="container mx-auto px-4">
      <h1 class="text-4xl font-bold text-center mb-12">Nos Produits Artisanaux</h1>
      
      <!-- Sculpture -->
      <section class="mb-20">
        <div class="grid md:grid-cols-2 gap-10 items-center">
          <div>
            <h2 class="text-3xl font-bold mb-6">Sculpture</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-6">
              Découvrez notre collection de sculptures traditionnelles en bois, incluant des masques, statues et meubles d'exception.
            </p>
            <ul class="space-y-2">
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Masques traditionnels
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Statues décoratives
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Meubles sculptés
              </li>
            </ul>
          </div>
          <div class="relative">
            <img src="/images/sculpture-detail.jpg" alt="Sculpture en bois" class="rounded-lg shadow-xl">
          </div>
        </div>
      </section>

      <!-- Bronze -->
      <section class="mb-20">
        <div class="grid md:grid-cols-2 gap-10 items-center">
          <div class="order-2 md:order-1">
            <img src="/images/bronze-detail.jpg" alt="Art en bronze" class="rounded-lg shadow-xl">
          </div>
          <div class="order-1 md:order-2">
            <h2 class="text-3xl font-bold mb-6">Bronze</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-6">
              Admirez nos œuvres en bronze, témoins de l'excellence de nos artisans dans le travail des métaux.
            </p>
            <ul class="space-y-2">
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Chevaux en bronze
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Masques décoratifs
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Objets d'art divers
              </li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Textile -->
      <section class="mb-20">
        <div class="grid md:grid-cols-2 gap-10 items-center">
          <div>
            <h2 class="text-3xl font-bold mb-6">Textile</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-6">
              Explorez notre collection de textiles traditionnels, mêlant authenticité et modernité.
            </p>
            <ul class="space-y-2">
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Tissus "Ndop"
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Tenues traditionnelles
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Accessoires stylisés
              </li>
            </ul>
          </div>
          <div class="relative">
            <img src="/images/textile-detail.jpg" alt="Textile traditionnel" class="rounded-lg shadow-xl">
          </div>
        </div>
      </section>

      <!-- Cosmétiques -->
      <section class="mb-20">
        <div class="grid md:grid-cols-2 gap-10 items-center">
          <div class="order-2 md:order-1">
            <img src="/images/cosmetique-detail.jpg" alt="Produits cosmétiques" class="rounded-lg shadow-xl">
          </div>
          <div class="order-1 md:order-2">
            <h2 class="text-3xl font-bold mb-6">Cosmétiques</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-6">
              Découvrez nos produits cosmétiques naturels, élaborés à partir de plantes locales.
            </p>
            <ul class="space-y-2">
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Shampoings naturels
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Savons aux plantes
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Laits de beauté
              </li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Agroalimentaire -->
      <section>
        <div class="grid md:grid-cols-2 gap-10 items-center">
          <div>
            <h2 class="text-3xl font-bold mb-6">Agroalimentaire</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-6">
              Savourez nos produits agroalimentaires traditionnels, issus de l'excellence de notre terroir.
            </p>
            <ul class="space-y-2">
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Vins de café et champignon
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Miel naturel
              </li>
              <li class="flex items-center">
                <span class="w-2 h-2 bg-primary rounded-full mr-2"></span>
                Produits à base de cacao
              </li>
            </ul>
          </div>
          <div class="relative">
            <img src="/images/agro-detail.jpg" alt="Produits agroalimentaires" class="rounded-lg shadow-xl">
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'default'
})
</script> 