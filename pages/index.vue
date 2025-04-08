<template>
  <div class="min-h-screen">
    <!-- Header -->
    <header class="border-b border-gray-200 dark:border-gray-800">
      <div class="container mx-auto px-4 py-4 flex justify-between items-center">
        <div class="flex items-center">
          <h1 class="text-2xl font-bold text-primary">TelesantePlus</h1>
        </div>

        <nav class="hidden md:flex space-x-6">
          <NuxtLink to="/" class="font-medium hover:text-primary transition-colors">
            Accueil
          </NuxtLink>
          <NuxtLink to="/services" class="font-medium hover:text-primary transition-colors">
            Services
          </NuxtLink>
          <NuxtLink to="/about" class="font-medium hover:text-primary transition-colors">
            À propos
          </NuxtLink>
          <NuxtLink to="/contact" class="font-medium hover:text-primary transition-colors">
            Contact
          </NuxtLink>
        </nav>

        <div class="flex items-center space-x-4">
          <UColorModeSelect />
        </div>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gray-50 dark:bg-gray-900">
      <div class="container mx-auto px-4 py-24">
        <div class="max-w-3xl mx-auto text-center">
          <h2 class="text-4xl md:text-5xl font-bold mb-6">
            Des soins de santé accessibles pour tous
          </h2>
          <p class="text-xl mb-8 text-gray-600 dark:text-gray-400">
            TelesantePlus vous connecte avec des professionnels de santé qualifiés à distance, pour des consultations
            simples et efficaces.
          </p>
          <div class="flex justify-center space-x-4">
            <UButton size="lg" color="primary">
              Prendre rendez-vous
            </UButton>
            <UButton size="lg" variant="outline">
              En savoir plus
            </UButton>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>