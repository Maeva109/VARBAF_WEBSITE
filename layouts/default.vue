<script setup lang="ts">
const isMenuOpen = ref(false)
</script>

<template>
  <div class="min-h-screen bg-gray-50 dark:bg-gray-900">
    <!-- Navigation -->
    <nav class="bg-white dark:bg-gray-800 shadow-lg">
      <div class="container mx-auto px-4">
        <div class="flex justify-between items-center h-16">
          <!-- Logo -->
          <div class="flex-shrink-0">
            <NuxtLink to="/" class="text-2xl font-bold text-primary">
              VARBAF
            </NuxtLink>
          </div>

          <!-- Navigation Desktop -->
          <div class="hidden md:flex items-center space-x-8">
            <NuxtLink to="/" class="text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Accueil
            </NuxtLink>
            <NuxtLink to="/produits" class="text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Produits
            </NuxtLink>
            <NuxtLink to="/galerie" class="text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Galerie
            </NuxtLink>
            <NuxtLink to="/actualites" class="text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Actualités
            </NuxtLink>
            <NuxtLink to="/contact" class="text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Contact
            </NuxtLink>
          </div>

          <!-- Bouton Menu Mobile -->
          <div class="md:hidden">
            <button @click="isMenuOpen = !isMenuOpen" class="text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              <svg v-if="!isMenuOpen" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
              </svg>
              <svg v-else class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
              </svg>
            </button>
          </div>
        </div>

        <!-- Menu Mobile -->
        <div v-show="isMenuOpen" class="md:hidden">
          <div class="px-2 pt-2 pb-3 space-y-1">
            <NuxtLink to="/" class="block px-3 py-2 rounded-md text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Accueil
            </NuxtLink>
            <NuxtLink to="/produits" class="block px-3 py-2 rounded-md text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Produits
            </NuxtLink>
            <NuxtLink to="/galerie" class="block px-3 py-2 rounded-md text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Galerie
            </NuxtLink>
            <NuxtLink to="/actualites" class="block px-3 py-2 rounded-md text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Actualités
            </NuxtLink>
            <NuxtLink to="/contact" class="block px-3 py-2 rounded-md text-gray-700 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
              Contact
            </NuxtLink>
          </div>
        </div>
      </div>
    </nav>

    <!-- Contenu principal -->
    <main>
      <slot />
    </main>

    <!-- Footer -->
    <footer class="bg-white dark:bg-gray-800 shadow-lg mt-20">
      <div class="container mx-auto px-4 py-12">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
          <!-- À propos -->
          <div>
            <h3 class="text-lg font-semibold mb-4">À propos</h3>
            <p class="text-gray-600 dark:text-gray-300">
              Le Village Artisanal Régional de Bafoussam est un espace d'encadrement collectif des artisans et entreprises artisanales.
            </p>
          </div>

          <!-- Liens rapides -->
          <div>
            <h3 class="text-lg font-semibold mb-4">Liens rapides</h3>
            <ul class="space-y-2">
              <li>
                <NuxtLink to="/produits" class="text-gray-600 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                  Nos produits
                </NuxtLink>
              </li>
              <li>
                <NuxtLink to="/galerie" class="text-gray-600 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                  Galerie photos
                </NuxtLink>
              </li>
              <li>
                <NuxtLink to="/actualites" class="text-gray-600 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                  Actualités
                </NuxtLink>
              </li>
              <li>
                <NuxtLink to="/contact" class="text-gray-600 dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                  Contact
                </NuxtLink>
              </li>
            </ul>
          </div>

          <!-- Contact -->
          <div>
            <h3 class="text-lg font-semibold mb-4">Contact</h3>
            <ul class="space-y-2">
              <li class="text-gray-600 dark:text-gray-300">
                Quartier TOKET, Carrefour Saint Thomas
              </li>
              <li class="text-gray-600 dark:text-gray-300">
                Bafoussam, Cameroun
              </li>
              <li class="text-gray-600 dark:text-gray-300">
                Tél: +237 XXX XXX XXX
              </li>
              <li class="text-gray-600 dark:text-gray-300">
                Email: contact@varbaf.cm
              </li>
            </ul>
          </div>

          <!-- Horaires -->
          <div>
            <h3 class="text-lg font-semibold mb-4">Horaires d'ouverture</h3>
            <ul class="space-y-2">
              <li class="text-gray-600 dark:text-gray-300">
                Lundi - Vendredi: 8h00 - 18h00
              </li>
              <li class="text-gray-600 dark:text-gray-300">
                Samedi: 9h00 - 16h00
              </li>
              <li class="text-gray-600 dark:text-gray-300">
                Dimanche: Fermé
              </li>
            </ul>
          </div>
        </div>

        <!-- Copyright -->
        <div class="border-t border-gray-200 dark:border-gray-700 mt-8 pt-8 text-center">
          <p class="text-gray-600 dark:text-gray-300">
            © {{ new Date().getFullYear() }} Village Artisanal Régional de Bafoussam. Tous droits réservés.
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>