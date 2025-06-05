<script setup>
definePageMeta({
  layout: 'default',
  title: 'VARBAF - Village Artisanal de Bafoussam',
  meta: [
    { name: 'description', content: 'Découvrez le Village Artisanal Régional de Bafoussam, un espace d\'encadrement collectif des artisans et entreprises artisanales.' }
  ]
})
</script>

<template>
  <div>
    <!-- Hero Section -->
    <section class="relative w-full bg-gradient-to-br from-primary/10 to-secondary/10">
      <div class="container mx-auto px-4 py-20">
        <div class="grid lg:grid-cols-2 gap-10 items-center">
          <div class="text-center lg:text-left">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-800 dark:text-white mb-6">
              Village Artisanal Régional de Bafoussam
            </h1>
            <p class="text-lg text-gray-600 dark:text-gray-300 mb-8">
              Découvrez l'excellence de l'artisanat camerounais dans un cadre unique de 4000m²
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
              <AtomsLinkBtn href="/visite" variant="primary">
                Planifier une visite
              </AtomsLinkBtn>
              <AtomsLinkBtn href="/produits" variant="secondary">
                Découvrir nos produits
              </AtomsLinkBtn>
            </div>
          </div>
          <div class="relative w-full h-96 rounded-lg overflow-hidden shadow-xl">
            <img
              src="/images/village-artisanal.jpg"
              alt="Village Artisanal de Bafoussam"
              class="w-full h-full object-cover"
            />
            <!-- Overlay décoratif optionnel -->
            <!-- <div class="absolute inset-0 bg-gradient-to-t from-black/30 to-transparent"></div> -->
          </div>
        </div>
      </div>
    </section>

    <!-- Présentation Section -->
    <section class="py-20 bg-white dark:bg-gray-900">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Notre Village Artisanal</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="p-6 bg-gray-50 dark:bg-gray-800 rounded-lg">
            <h3 class="text-xl font-semibold mb-4">Notre Mission</h3>
            <p class="text-gray-600 dark:text-gray-300">
              Encadrer et promouvoir les artisans locaux dans la production, l'exposition et la commercialisation de leurs œuvres.
            </p>
          </div>
          <div class="p-6 bg-gray-50 dark:bg-gray-800 rounded-lg">
            <h3 class="text-xl font-semibold mb-4">Nos Installations</h3>
            <p class="text-gray-600 dark:text-gray-300">
              Boutiques d'exposition, salles de formation, ateliers de production, restaurant et espaces événementiels.
            </p>
          </div>
          <div class="p-6 bg-gray-50 dark:bg-gray-800 rounded-lg">
            <h3 class="text-xl font-semibold mb-4">Notre Emplacement</h3>
            <p class="text-gray-600 dark:text-gray-300">
              Situé au quartier TOKET, Carrefour Saint Thomas, entre la Préfecture et le Conseil régional de l'Ouest.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Produits Phares Section -->
    <section class="py-20 bg-gray-50 dark:bg-gray-800">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Nos Produits Phares</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white dark:bg-gray-900 rounded-lg overflow-hidden shadow-lg">
            <img src="/images/sculpture.jpg" alt="Sculpture" class="w-full h-48 object-cover">
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2">Sculpture</h3>
              <p class="text-gray-600 dark:text-gray-300">
                Masques, statues et meubles en bois traditionnels
              </p>
            </div>
          </div>
          <div class="bg-white dark:bg-gray-900 rounded-lg overflow-hidden shadow-lg">
            <img src="/images/bronze.jpg" alt="Bronze" class="w-full h-48 object-cover">
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2">Bronze</h3>
              <p class="text-gray-600 dark:text-gray-300">
                Chevaux, masques et objets d'art en bronze
              </p>
            </div>
          </div>
          <div class="bg-white dark:bg-gray-900 rounded-lg overflow-hidden shadow-lg">
            <img src="/images/textile.jpg" alt="Textile" class="w-full h-48 object-cover">
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2">Textile</h3>
              <p class="text-gray-600 dark:text-gray-300">
                Habits traditionnels et tissus "Ndop" stylisés
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 bg-primary text-white">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold mb-6">Venez découvrir notre village artisanal</h2>
        <p class="text-lg mb-8">Une expérience unique au cœur de l'artisanat camerounais</p>
        <AtomsLinkBtn href="/contact" variant="white">
          Nous contacter
        </AtomsLinkBtn>
      </div>
    </section>
  </div>
</template>