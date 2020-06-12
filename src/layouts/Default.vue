<template>
  <div class="text-green-600 font-light">
    <nav class="flex items-center justify-between border-b border-green-600 h-16 px-4 md:px-6">
      <div class="text-xl">
        <i class="fas fa-bacterium"></i>
        <a href="/">posalusa24</a>
      </div>
      <div class="flex flex-grow items-center justify-end h-full">
        <div class="w-10 md:w-12 text-center md:rounded-md md:px-2 md:py-1 hover:bg-green-100 hover:font-normal">
          <g-link to="/">me</g-link>
        </div>
        <div class="w-16 md:w-20 text-center md:rounded-md md:px-2 md:py-1 hover:bg-green-100 hover:font-normal">
          <g-link to="/projects/">projects</g-link>
        </div>
        <div class="w-10 md:w-12 text-center md:rounded-md md:px-2 md:py-1 hover:bg-green-100 hover:font-normal">
          <g-link to="/blog/">blog</g-link>
        </div>
      </div>
    </nav>
    <slot />
    <footer class="border-t border-green-600 text-sm text-center py-1 mt-10">
      made with gridsome &amp; tailwindcss
    </footer>
  </div>
</template>
