<template>
  <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Security Projects</h2>
        <p class="mt-2 text-lg leading-8 text-gray-600">Browse open cybersecurity projects and submit your proposals.</p>
      </div>
      <div class="mx-auto mt-10 grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 border-t border-gray-200 pt-10 sm:mt-16 sm:pt-16 lg:mx-0 lg:max-w-none lg:grid-cols-3">
        <!-- Example Project Card - Replace with real data -->
        <article class="flex max-w-xl flex-col items-start">
          <div class="flex items-center gap-x-4 text-xs">
            <time datetime="2024-03-16" class="text-gray-500">Mar 16, 2024</time>
            <span class="relative z-10 rounded-full bg-green-50 px-3 py-1.5 font-medium text-green-600">Open</span>
          </div>
          <div class="group relative">
            <h3 class="mt-3 text-lg font-semibold leading-6 text-gray-900 group-hover:text-gray-600">
              <NuxtLink to="/projects/1">
                <span class="absolute inset-0"></span>
                Security Audit for E-commerce Platform
              </NuxtLink>
            </h3>
            <p class="mt-5 line-clamp-3 text-sm leading-6 text-gray-600">Looking for a security professional to conduct a comprehensive security audit of our e-commerce platform. Must have experience with PCI DSS compliance.</p>
          </div>
          <div class="mt-8 flex items-center gap-x-4">
            <div class="text-sm leading-6">
              <p class="font-semibold text-gray-900">Budget: $5,000 - $8,000</p>
              <p class="text-gray-600">Duration: 2-3 weeks</p>
            </div>
          </div>
        </article>

        <!-- Add more project cards here -->
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  title: 'Projects'
})
</script> 