<template>
  <header class="">
    <nav class="mx-auto max-w-7xl flex items-center justify-between p-6 lg:px-8" aria-label="Global">
      <div class="flex lg:flex-1">
        <NuxtLink to="/" class="p-1.5 -m-1.5">
          <span class="text-2xl font-medium text-teal-600 dark:text-teal-400">Guillermo Gil</span>
          <!-- <span class="sr-only">Guillermo Gil</span> -->
          <!-- <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600" alt=""> -->
        </NuxtLink>
      </div>
      <div class="flex flex-1 justify-end gap-2">
        <NuxtLink to="https://www.linkedin.com/in/guillegil" class="i-carbon-logo-linkedin social-icon" />
        <NuxtLink to="https://github.com/guillegil" class="i-carbon-logo-github social-icon" />
        <NuxtLink to="https://twitter.com/guillegilrod" class="i-carbon-logo-twitter social-icon" />
        <DarkToggle />
      </div>
    </nav>
  </header>
</template>
