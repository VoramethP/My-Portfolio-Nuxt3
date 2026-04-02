<template>
  <header class="sticky top-0 z-50 bg-white/80 dark:bg-gray-950/80 backdrop-blur-md border-b border-gray-200 dark:border-gray-800">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      
      <NuxtLink to="/" class="font-bold text-xl tracking-tight text-gray-900 dark:text-white">
        Tes<span class="text-primary-500">.</span>
      </NuxtLink>

      <nav class="hidden sm:flex items-center gap-6">
        <NuxtLink to="/" class="text-sm font-medium text-gray-600 hover:text-gray-900 dark:text-gray-400 dark:hover:text-white transition-colors">
          Home
        </NuxtLink>
        <NuxtLink to="#projects" class="text-sm font-medium text-gray-600 hover:text-gray-900 dark:text-gray-400 dark:hover:text-white transition-colors">
          Projects
        </NuxtLink>
        <NuxtLink to="#experience" class="text-sm font-medium text-gray-600 hover:text-gray-900 dark:text-gray-400 dark:hover:text-white transition-colors">
          Experience
        </NuxtLink>
      </nav>

      <div class="flex items-center gap-3">
        <UButton color="neutral" variant="ghost" icon="i-heroicons-moon" class="hidden sm:inline-flex" />
        
        <UButton color="primary" variant="solid" size="sm">
          Resume
        </UButton>
      </div>

    </div>
  </header>
</template>