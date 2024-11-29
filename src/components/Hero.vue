<template>
  <div class="relative px-6 pt-1 lg:px-8">
    <div class="mx-auto max-w-7xl lg:flex lg:items-center lg:justify-between">
      <div class="text-center lg:text-left lg:max-w-lg animate-fadeIn">
        <h1 class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl">
          <span class="block">Professional Cleaning Services</span>
        </h1>
        <p class=" mt-8 text-lg font-medium text-gray-500 sm:text-xl">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore
          magna aliqua.
        </p>
        <div class="mt-10 flex items-center justify-center lg:justify-start gap-x-6">
          <a href="#"
            class="bg-yellow-500 shadow-lg shadow-yellow-500/50 px-4 py-2.5 text-sm/6 font-semibold text-white border border-transparent rounded-md hover:bg-yellow-600 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-yellow-600">Pesan
            Sekarang !</a>
          <a href="#" class="text-sm/6 font-semibold text-gray-900">Learn more <span aria-hidden="true">→</span></a>
        </div>
      </div>
      <div
        class="mt-12 lg:mt-0 lg:max-w-lg hidden lg:block transition ease-in-out duration-300 transform hover:scale-105 animate-fadeIn bg-transparent">
        <img src="../assets/img/cleaning-service.png" alt="Hero Image" class="w-full h-auto" />
      </div>
    </div>
  </div>
</template>

<style scoped>
@keyframes fadeIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

.animate-fadeIn {
  animation: fadeIn 2s ease-out;
}
</style>
