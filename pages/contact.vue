<template>
  <div class="py-20">
    <div class="container mx-auto px-4">
      <h1 class="text-4xl font-bold text-center mb-12">Contactez-nous</h1>

      <div class="grid lg:grid-cols-2 gap-12">
        <!-- Informations de contact -->
        <div>
          <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
            <h2 class="text-2xl font-bold mb-6">Nos coordonnées</h2>
            
            <div class="space-y-6">
              <div class="flex items-start">
                <div class="flex-shrink-0">
                  <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                  </svg>
                </div>
                <div class="ml-4">
                  <h3 class="text-lg font-semibold">Adresse</h3>
                  <p class="text-gray-600 dark:text-gray-300">
                    Village Artisanal Régional de Bafoussam<br>
                    Quartier TOKET, Carrefour Saint Thomas<br>
                    Entre la Préfecture et le Conseil régional de l'Ouest<br>
                    Bafoussam, Cameroun
                  </p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="flex-shrink-0">
                  <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                  </svg>
                </div>
                <div class="ml-4">
                  <h3 class="text-lg font-semibold">Email</h3>
                  <p class="text-gray-600 dark:text-gray-300">
                    contact@varbaf.cm
                  </p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="flex-shrink-0">
                  <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                  </svg>
                </div>
                <div class="ml-4">
                  <h3 class="text-lg font-semibold">Téléphone</h3>
                  <p class="text-gray-600 dark:text-gray-300">
                    +237 XXX XXX XXX
                  </p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="flex-shrink-0">
                  <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
                  </svg>
                </div>
                <div class="ml-4">
                  <h3 class="text-lg font-semibold">Horaires d'ouverture</h3>
                  <p class="text-gray-600 dark:text-gray-300">
                    Lundi - Vendredi: 8h00 - 18h00<br>
                    Samedi: 9h00 - 16h00<br>
                    Dimanche: Fermé
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Formulaire de contact -->
        <div>
          <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
            <h2 class="text-2xl font-bold mb-6">Envoyez-nous un message</h2>
            
            <form class="space-y-6">
              <div>
                <label for="name" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Nom complet</label>
                <input type="text" id="name" name="name" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary">
              </div>

              <div>
                <label for="email" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Email</label>
                <input type="email" id="email" name="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary">
              </div>

              <div>
                <label for="subject" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Sujet</label>
                <input type="text" id="subject" name="subject" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary">
              </div>

              <div>
                <label for="message" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Message</label>
                <textarea id="message" name="message" rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary"></textarea>
              </div>

              <div>
                <button type="submit" class="w-full flex justify-center py-2 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-primary hover:bg-primary-dark focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-primary">
                  Envoyer le message
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>

      <!-- Carte -->
      <div class="mt-12">
        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
          <h2 class="text-2xl font-bold mb-6">Notre localisation</h2>
          <div class="aspect-w-16 aspect-h-9">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3989.7536223157963!2d10.4175993!3d5.4775519!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNcKwMjgnMzkuMiJOIDEwwrAyNScwMy4zIkU!5e0!3m2!1sfr!2scm!4v1635000000000!5m2!1sfr!2scm"
              width="100%"
              height="450"
              style="border:0;"
              allowfullscreen=""
              loading="lazy"
              class="rounded-lg"
            ></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'default'
})
</script> 