import { UBadge, UButton, UCard } from '@nuxt/ui'
impoert TemplateMenu from '~/components/TemplateMenu.vue'
import { UDropdownMenu } from '@nuxt/ui'

<template>
  <!-- Hero Section -->
  <div class="py-24 sm:py-32 flex flex-col items-center text-center">
    
    <UBadge color="primary" variant="subtle" class="mb-6 rounded-full px-4 py-1.5 font-medium">
      Open to Data Analytics & Web Scraping Roles
    </UBadge>

    <h1 class="text-5xl font-extrabold tracking-tight text-gray-900 dark:text-white sm:text-7xl">
      Hi, I'm Tes.
    </h1>
    
    <h2 class="mt-4 text-3xl font-bold tracking-tight text-gray-700 dark:text-gray-300 sm:text-5xl">
      Full Stack Developer.
    </h2>

    <p class="mt-6 text-lg leading-8 text-gray-600 dark:text-gray-400 max-w-2xl">
      I'm a product-minded engineer based in Bangkok, blending clean code with intuitive UI/UX design. Whether I'm building smart AIoT systems or data-driven web applications, I focus on creating seamless digital experiences.
    </p>

    <div class="mt-10 flex items-center justify-center gap-x-4">
      <UButton size="xl" color="primary" variant="solid">
        View My Work
      </UButton>
      <UButton size="xl" color="neutral" variant="ghost" to="https://github.com/VoramethP" target="_blank">
        GitHub Profile
      </UButton>
    </div>

  </div>

  <!-- Featured Projects -->
  <div class="py-16 sm:py-24">
      <div class="mx-auto max-w-7xl">
        <div class="mb-12 text-center">
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white sm:text-4xl">
            Featured Projects
          </h2>
          <p class="mt-4 text-lg text-gray-600 dark:text-gray-400">
            A selection of my recent work across full-stack development, AIoT, and UI/UX design.
          </p>
        </div>

        <div class="grid grid-cols-1 gap-8 lg:grid-cols-2">
          
          <UCard class="flex flex-col">
            <template #header>
              <div class="flex justify-between items-start">
                <div>
                  <h3 class="text-xl font-bold text-gray-900 dark:text-white">Smart Hospital Delivery</h3>
                  <p class="text-sm font-medium text-primary-500 mt-1">1st Place - AdvanTECH AIoT Innoworks</p>
                </div>
                <UButton icon="i-heroicons-arrow-top-right-on-square" color="neutral" variant="ghost" />
              </div>
            </template>
            <p class="text-gray-600 dark:text-gray-400 flex-grow">
              An IoT-based automated delivery system designed to optimize food logistics within hospital environments, focusing on efficiency and hygiene.
            </p>
            <template #footer>
              <div class="flex flex-wrap gap-2">
                <UBadge color="info" variant="solid">IoT</UBadge>
                <UBadge color="info" variant="solid">Python</UBadge>
                <UBadge color="info" variant="solid">Hardware Integration</UBadge>
              </div>
            </template>
          </UCard>

          <UCard class="flex flex-col">
            <template #header>
              <div class="flex justify-between items-start">
                <div>
                  <h3 class="text-xl font-bold text-gray-900 dark:text-white">Shifts</h3>
                  <p class="text-sm font-medium text-gray-500 dark:text-gray-400 mt-1">Gym & Meal Tracking Application</p>
                </div>
                <UButton icon="i-heroicons-arrow-top-right-on-square" color="neutral" variant="ghost" />
              </div>
            </template>
            <p class="text-gray-600 dark:text-gray-400 flex-grow">
              A comprehensive health application bridging the gap between fitness routines and nutritional planning with an intuitive UI/UX.
            </p>
            <template #footer>
              <div class="flex flex-wrap gap-2">
                <UBadge color="info" variant="solid">Frontend</UBadge>
                <UBadge color="info" variant="solid">UI/UX Design</UBadge>
              </div>
            </template>
          </UCard>

          <UCard class="flex flex-col">
            <template #header>
              <div class="flex justify-between items-start">
                <div>
                  <h3 class="text-xl font-bold text-gray-900 dark:text-white">Kidney Stone Detector</h3>
                  <p class="text-sm font-medium text-gray-500 dark:text-gray-400 mt-1">Healthcare Data Analytics</p>
                </div>
                <UButton icon="i-heroicons-arrow-top-right-on-square" color="neutral" variant="ghost" />
              </div>
            </template>
            <p class="text-gray-600 dark:text-gray-400 flex-grow">
              An analytical tool built to process and evaluate medical data for the detection and assessment of kidney stones.
            </p>
            <template #footer>
              <div class="flex flex-wrap gap-2">
                <UBadge color="info" variant="solid">Data Analytics</UBadge>
                <UBadge color="info" variant="solid">Python</UBadge>
              </div>
            </template>
          </UCard>

          <UCard class="flex flex-col">
            <template #header>
              <div class="flex justify-between items-start">
                <div>
                  <h3 class="text-xl font-bold text-gray-900 dark:text-white">Basetone Official</h3>
                  <p class="text-sm font-medium text-gray-500 dark:text-gray-400 mt-1">E-Commerce & Brand Identity</p>
                </div>
                <UButton icon="i-heroicons-arrow-top-right-on-square" color="neutral" variant="ghost" />
              </div>
            </template>
            <p class="text-gray-600 dark:text-gray-400 flex-grow">
              Developed the digital storefront and modern brand identity for a street and playful clothing label.
            </p>
            <template #footer>
              <div class="flex flex-wrap gap-2">
                <UBadge color="info" variant="solid">Web Development</UBadge>
                <UBadge color="info" variant="solid">Branding</UBadge>
              </div>
            </template>
          </UCard>

        </div>
      </div>
    </div>

    <!-- experiences -->
     <div class="py-16 sm:py-24 bg-gray-50 dark:bg-gray-900/50 rounded-3xl my-12 max-w-4xl mx-auto px-6 sm:px-12">
      
      <div class="mb-10 text-center">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white">
          Experience & Leadership
        </h2>
      </div>

      <div class="space-y-6">
        
        <UCard class="ring-1 ring-gray-200 dark:ring-gray-800, shadow-none">
          <div class="flex flex-col sm:flex-row sm:items-center justify-between">
            <div>
              <h3 class="text-lg font-bold text-gray-900 dark:text-white">Full Stack Intern</h3>
              <p class="text-primary-500 font-medium">CardX</p>
            </div>
            <span class="text-sm text-gray-500 mt-2 sm:mt-0 font-mono">Recent</span>
          </div>
          <p class="mt-4 text-gray-600 dark:text-gray-400 text-sm">
            Contributed to fintech development cycles, gaining hands-on experience building robust, scalable solutions in a fast-paced professional environment.
          </p>
        </UCard>

        <UCard class="ring-1 ring-gray-200 dark:ring-gray-800, shadow-none">
          <div class="flex flex-col sm:flex-row sm:items-center justify-between">
            <div>
              <h3 class="text-lg font-bold text-gray-900 dark:text-white">Teaching Assistant</h3>
              <p class="text-primary-500 font-medium">Programming & Networking</p>
            </div>
            <span class="text-sm text-gray-500 mt-2 sm:mt-0 font-mono">Academic Roles</span>
          </div>
          <p class="mt-4 text-gray-600 dark:text-gray-400 text-sm">
            Mentored university students across multiple institutions, breaking down complex programming logic and guiding them through foundational networking concepts.
          </p>
        </UCard>

        <UCard class="ring-1 ring-gray-200 dark:ring-gray-800, shadow-none">
          <div class="flex flex-col sm:flex-row sm:items-center justify-between">
            <div>
              <h3 class="text-lg font-bold text-gray-900 dark:text-white">Vice President</h3>
              <p class="text-primary-500 font-medium">ITD Faculty Student Council</p>
            </div>
            <span class="text-sm text-gray-500 mt-2 sm:mt-0 font-mono">Jun 2023 - May 2024</span>
          </div>
          <p class="mt-4 text-gray-600 dark:text-gray-400 text-sm">
            Directed student initiatives, organized faculty-wide events, and acted as a liaison between the student body and university administration.
          </p>
        </UCard>

      </div>
    </div>
</template>