<template>
  <div class="py-20">
    <div class="container mx-auto px-4">
      <h1 class="text-4xl font-bold text-center mb-12">Actualités & Événements</h1>

      <!-- Filtres -->
      <div class="flex justify-center mb-12 space-x-4">
        <button class="px-4 py-2 rounded-full bg-primary text-white hover:bg-primary-dark">
          Tous
        </button>
        <button class="px-4 py-2 rounded-full bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
          Événements
        </button>
        <button class="px-4 py-2 rounded-full bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
          Actualités
        </button>
      </div>

      <!-- Grille d'articles -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Article 1 -->
        <article class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden">
          <img src="/images/event1.jpg" alt="Inauguration" class="w-full h-48 object-cover">
          <div class="p-6">
            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400 mb-2">
              <span>10 Mars 2021</span>
              <span class="mx-2">•</span>
              <span>Événement</span>
            </div>
            <h2 class="text-xl font-bold mb-2">Inauguration du Village Artisanal</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">
              Le Village Artisanal Régional de Bafoussam a été inauguré en présence des autorités locales...
            </p>
            <a href="#" class="text-primary hover:text-primary-dark font-medium">
              Lire la suite →
            </a>
          </div>
        </article>

        <!-- Article 2 -->
        <article class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden">
          <img src="/images/event2.jpg" alt="Formation" class="w-full h-48 object-cover">
          <div class="p-6">
            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400 mb-2">
              <span>15 Avril 2021</span>
              <span class="mx-2">•</span>
              <span>Formation</span>
            </div>
            <h2 class="text-xl font-bold mb-2">Formation des Artisans</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">
              Une session de formation sur les techniques modernes de sculpture a été organisée...
            </p>
            <a href="#" class="text-primary hover:text-primary-dark font-medium">
              Lire la suite →
            </a>
          </div>
        </article>

        <!-- Article 3 -->
        <article class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden">
          <img src="/images/event3.jpg" alt="Exposition" class="w-full h-48 object-cover">
          <div class="p-6">
            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400 mb-2">
              <span>1 Mai 2021</span>
              <span class="mx-2">•</span>
              <span>Exposition</span>
            </div>
            <h2 class="text-xl font-bold mb-2">Exposition de Textiles</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">
              Une exposition exceptionnelle de textiles traditionnels a été organisée...
            </p>
            <a href="#" class="text-primary hover:text-primary-dark font-medium">
              Lire la suite →
            </a>
          </div>
        </article>

        <!-- Article 4 -->
        <article class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden">
          <img src="/images/event4.jpg" alt="Foire" class="w-full h-48 object-cover">
          <div class="p-6">
            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400 mb-2">
              <span>20 Juin 2021</span>
              <span class="mx-2">•</span>
              <span>Foire</span>
            </div>
            <h2 class="text-xl font-bold mb-2">Foire Artisanale</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">
              La première foire artisanale annuelle a accueilli plus de 1000 visiteurs...
            </p>
            <a href="#" class="text-primary hover:text-primary-dark font-medium">
              Lire la suite →
            </a>
          </div>
        </article>

        <!-- Article 5 -->
        <article class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden">
          <img src="/images/event5.jpg" alt="Atelier" class="w-full h-48 object-cover">
          <div class="p-6">
            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400 mb-2">
              <span>5 Juillet 2021</span>
              <span class="mx-2">•</span>
              <span>Atelier</span>
            </div>
            <h2 class="text-xl font-bold mb-2">Atelier de Poterie</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">
              Un atelier de poterie traditionnelle a été organisé pour les jeunes artisans...
            </p>
            <a href="#" class="text-primary hover:text-primary-dark font-medium">
              Lire la suite →
            </a>
          </div>
        </article>

        <!-- Article 6 -->
        <article class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden">
          <img src="/images/event6.jpg" alt="Visite" class="w-full h-48 object-cover">
          <div class="p-6">
            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400 mb-2">
              <span>15 Août 2021</span>
              <span class="mx-2">•</span>
              <span>Visite</span>
            </div>
            <h2 class="text-xl font-bold mb-2">Visite Officielle</h2>
            <p class="text-gray-600 dark:text-gray-300 mb-4">
              Une délégation ministérielle a visité le village artisanal...
            </p>
            <a href="#" class="text-primary hover:text-primary-dark font-medium">
              Lire la suite →
            </a>
          </div>
        </article>
      </div>

      <!-- Pagination -->
      <div class="flex justify-center mt-12">
        <nav class="flex items-center space-x-2">
          <button class="px-3 py-1 rounded-md bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
            Précédent
          </button>
          <button class="px-3 py-1 rounded-md bg-primary text-white">
            1
          </button>
          <button class="px-3 py-1 rounded-md bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
            2
          </button>
          <button class="px-3 py-1 rounded-md bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
            3
          </button>
          <button class="px-3 py-1 rounded-md bg-gray-100 dark:bg-gray-800 hover:bg-gray-200 dark:hover:bg-gray-700">
            Suivant
          </button>
        </nav>
      </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'default'
})
</script> 