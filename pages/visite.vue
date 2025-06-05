<template>
  <div class="py-20">
    <div class="container mx-auto px-4">
      <h1 class="text-4xl font-bold text-center mb-12">Planifier une visite</h1>
      <div class="grid md:grid-cols-2 gap-12">
        <!-- Infos pratiques -->
        <div>
          <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-2xl font-bold mb-4">Informations pratiques</h2>
            <ul class="space-y-4 text-gray-600 dark:text-gray-300">
              <li><strong>Adresse :</strong> Quartier TOKET, Carrefour Saint Thomas, Bafoussam, Cameroun</li>
              <li><strong>Horaires :</strong> Lundi - Vendredi : 8h00 - 18h00<br>Samedi : 9h00 - 16h00<br>Dimanche : Fermé</li>
              <li><strong>Accès :</strong> Entre la Préfecture et le Conseil régional de l'Ouest. Parking gratuit sur place.</li>
              <li><strong>Contact :</strong> <a href="mailto:contact@varbaf.cm" class="text-primary hover:underline">contact@varbaf.cm</a> / +237 XXX XXX XXX</li>
            </ul>
          </div>
          <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
            <h2 class="text-2xl font-bold mb-4">À quoi s'attendre ?</h2>
            <ul class="list-disc pl-6 text-gray-600 dark:text-gray-300 space-y-2">
              <li>Visite guidée des ateliers et boutiques</li>
              <li>Découverte des savoir-faire artisanaux locaux</li>
              <li>Rencontre avec les artisans</li>
              <li>Dégustation de produits locaux (selon disponibilité)</li>
              <li>Possibilité d'achat sur place</li>
            </ul>
          </div>
        </div>
        <!-- Formulaire de demande de visite -->
        <div>
          <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
            <h2 class="text-2xl font-bold mb-6">Demander une visite</h2>
            <form class="space-y-6">
              <div>
                <label for="nom" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Nom complet</label>
                <input type="text" id="nom" name="nom" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary">
              </div>
              <div>
                <label for="email" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Email</label>
                <input type="email" id="email" name="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary">
              </div>
              <div>
                <label for="date" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Date souhaitée</label>
                <input type="date" id="date" name="date" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary">
              </div>
              <div>
                <label for="message" class="block text-sm font-medium text-gray-700 dark:text-gray-300">Message (optionnel)</label>
                <textarea id="message" name="message" rows="3" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-primary focus:ring-primary"></textarea>
              </div>
              <div>
                <button type="submit" class="w-full flex justify-center py-2 px-4 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-primary hover:bg-primary-dark focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-primary">
                  Envoyer la demande
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
      <!-- Carte -->
      <div class="mt-12">
        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
          <h2 class="text-2xl font-bold mb-6">Localisation</h2>
          <div class="aspect-w-16 aspect-h-9">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3989.7536223157963!2d10.4175993!3d5.4775519!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNcKwMjgnMzkuMiJOIDEwwrAyNScwMy4zIkU!5e0!3m2!1sfr!2scm!4v1635000000000!5m2!1sfr!2scm"
              width="100%"
              height="350"
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
  layout: 'default',
  title: 'Planifier une visite - VARBAF',
  meta: [
    { name: 'description', content: 'Planifiez votre visite au Village Artisanal Régional de Bafoussam. Découvrez les horaires, modalités et réservez votre visite guidée.' }
  ]
})
</script> 