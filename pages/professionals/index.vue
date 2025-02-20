<template>
  <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Security Professionals</h2>
        <p class="mt-2 text-lg leading-8 text-gray-600">Find and hire top cybersecurity experts for your projects.</p>
      </div>
      <div class="mx-auto mt-10 grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 border-t border-gray-200 pt-10 sm:mt-16 sm:pt-16 lg:mx-0 lg:max-w-none lg:grid-cols-3">
        <!-- Example Professional Card - Replace with real data -->
        <article class="flex max-w-xl flex-col items-start justify-between">
          <div class="flex items-center gap-x-4 text-xs">
            <span class="relative z-10 rounded-full bg-blue-50 px-3 py-1.5 font-medium text-blue-600">Security Analyst</span>
            <span class="relative z-10 rounded-full bg-gray-50 px-3 py-1.5 font-medium text-gray-600">5 years exp.</span>
          </div>
          <div class="group relative">
            <h3 class="mt-3 text-lg font-semibold leading-6 text-gray-900 group-hover:text-gray-600">
              <NuxtLink to="/professionals/1">
                <span class="absolute inset-0"></span>
                John Smith
              </NuxtLink>
            </h3>
            <p class="mt-5 line-clamp-3 text-sm leading-6 text-gray-600">
              Certified security professional specializing in penetration testing and vulnerability assessment. Experience with OWASP Top 10, network security, and cloud infrastructure.
            </p>
          </div>
          <div class="mt-8 flex items-center gap-x-4">
            <img src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="" class="h-10 w-10 rounded-full bg-gray-50">
            <div class="text-sm leading-6">
              <p class="font-semibold text-gray-900">
                <NuxtLink to="/professionals/1">
                  <span class="absolute inset-0"></span>
                  John Smith
                </NuxtLink>
              </p>
              <p class="text-gray-600">Security Analyst</p>
            </div>
          </div>
        </article>

        <!-- Add more professional cards here -->
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  title: 'Professionals'
})
</script> 