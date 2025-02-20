<template>
  <div class="min-h-screen bg-gray-50">
    <header class="bg-white shadow">
      <nav class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8" aria-label="Top">
        <div class="flex h-16 items-center justify-between">
          <div class="flex items-center">
            <NuxtLink to="/" class="text-2xl font-bold text-primary-600">
              CyberBid
            </NuxtLink>
          </div>
          <div class="ml-10 space-x-4">
            <NuxtLink to="/projects" class="text-base font-medium text-gray-500 hover:text-gray-900">
              Projects
            </NuxtLink>
            <NuxtLink to="/professionals" class="text-base font-medium text-gray-500 hover:text-gray-900">
              Professionals
            </NuxtLink>
            <NuxtLink to="/about" class="text-base font-medium text-gray-500 hover:text-gray-900">
              About
            </NuxtLink>
          </div>
        </div>
      </nav>
    </header>

    <main>
      <NuxtPage />
    </main>

    <footer class="bg-white mt-auto">
      <div class="mx-auto max-w-7xl px-4 py-12 sm:px-6 lg:px-8">
        <div class="border-t border-gray-200 pt-8">
          <p class="text-base text-gray-400 text-center">
            &copy; {{ new Date().getFullYear() }} CyberBid. All rights reserved.
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
html {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}</style>
