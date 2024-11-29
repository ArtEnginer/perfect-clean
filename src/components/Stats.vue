<template>
  <div class="bg-gray-50 py-3">
    <div class="mx-auto max-w-7xl px-1 lg:px-8">
      <dl class="grid grid-cols-1 gap-x-2 gap-y-2 text-center lg:grid-cols-3 ">
        <div v-for="stat in stats" :key="stat.id"
          :class="['flex flex-col items-center justify-center shadow-black-500/50 rounded-md animate-fadeIn', stat.bgcolor]">
          <dt class="text-base/7 text-white">{{ stat.name }}</dt>
          <dd class="order-first text-1xl font-semibold tracking-tight text-gray-900 sm:text-2xl text-white">
            {{ stat.value }}
          </dd>
        </div>
      </dl>
    </div>
  </div>
</template>

<script setup>
const stats = [
  { id: 1, name: 'Pelanggan Terlayani', value: '500+ Pelanggan', bgcolor: 'bg-green-500' },
  { id: 2, name: 'Pekerjaan Selesai', value: '1,000+ Pekerjaan', bgcolor: 'bg-blue-500' },
  { id: 3, name: 'Karyawan Berpengalaman', value: '50+ Karyawan', bgcolor: 'bg-yellow-500' }
]
</script>

<style scoped>
/* buatkan animasi fade in .stats*/
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
