<template>
  <section class="py-2 bg-base-200">
    <div class="container mx-auto px-6 lg:px-8">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Our Gallery</h2>
        <p class="mt-2 text-lg font-medium text-gray-500 sm:text-xl italic">See our cleaning services in action.</p>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-4">
        <div
          class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
          <figure class="relative h-60">
            <img :src="gallery1" alt="Gallery 1" class="w-full h-full object-cover" />
          </figure>
        </div>
        <div
          class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
          <figure class="relative h-60">
            <img :src="gallery2" alt="Gallery 2" class="w-full h-full object-cover" />
          </figure>
        </div>
        <div
          class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
          <figure class="relative h-60">
            <img :src="gallery3" alt="Gallery 3" class="w-full h-full object-cover" />
          </figure>
        </div>
        <div
          class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
          <figure class="relative h-60">
            <img :src="gallery4" alt="Gallery 4" class="w-full h-full object-cover" />
          </figure>
        </div>
        <div
          class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
          <figure class="relative h-60">
            <img :src="gallery5" alt="Gallery 5" class="w-full h-full object-cover" />
          </figure>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Gallery1 from '../assets/img/g1.png';
import Gallery2 from '../assets/img/g2.png';
import Gallery3 from '../assets/img/g3.png';
import Gallery4 from '../assets/img/g4.png';
import Gallery5 from '../assets/img/g5.png';

export default {
  setup() {
    // Add any reactive variables here
  },

  data() {
    return {
      gallery1: Gallery1,
      gallery2: Gallery2,
      gallery3: Gallery3,
      gallery4: Gallery4,
      gallery5: Gallery5,
    }
  },

}
</script>
