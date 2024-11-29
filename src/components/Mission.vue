<template>
    <section class="pt-14 flex items-center bg-gray-50">

        <div class="container max-w-7xl mx-auto px-4 flex flex-col lg:flex-row items-center gap-8 lg:gap-14">
            <figure class="relative w-full lg:w-1/2 ">
                <img :src="aboutImage" alt="cs" class="w-full h-auto object-cover rounded-xl" />
                <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent rounded-xl">
                </div>
                <div
                    class="absolute top-8 left-4 tracking-wide px-3 py-1 rounded-3xl text-lg sm:text-xl text-start italic">
                    "Perusahaan Jasa <br> Cleaning Service Profesional" <br>
                    <span class="text-sm font-bold">
                        "Sudah lebih dari 1 tahun memberikan pelayanan terbaik"
                    </span>
                </div>
                <div
                    class="absolute bottom-4 left-4 text-white tracking-wide px-3 py-1 rounded-3xl text-base sm:text-xl text-start italic">
                    <img :src="logo" alt="" width="90" class="opacity-75" />
                </div>
            </figure>

            <div class="text-start w-full lg:w-1/2">
                <h2 class="text-md sm:text-lg font-semibold text-gray-400">Tentang Kami</h2>
                <p
                    class="mt-2 max-w-full text-1xl sm:text-2xl text-gray-900 font-bold leading-relaxed tracking-wide border-b pb-5">
                    "Kami adalah perusahaan jasa cleaning service profesional yang berdiri sejak 2020. Kami memberikan
                    pelayanan terbaik untuk kebersihan dan kesehatan lingkungan anda. Kami memiliki tim yang profesional
                    dan berpengalaman dalam memberikan pelayanan terbaik untuk anda. Kami siap membantu anda dalam
                    membersihkan rumah, kantor, apartemen, dan lainnya."
                </p>

                <div class="mt-6 flex flex-wrap gap-4 sm:gap-6">
                    <img :src="folio1" alt="folio-1" class="w-20" />
                    <img :src="folio2" alt="folio-2" class="w-20" />
                    <img :src="folio3" alt="folio-3" class="w-20" />
                </div>
            </div>
        </div>
    </section>
</template>

<script>

import About1 from '../assets/img/cs-1.png';
import logo from '../assets/logo.png';
import folio1 from '../assets/img/cs-2.png';
import folio2 from '../assets/img/cs-3.png';
import folio3 from '../assets/img/cs-4.png';

export default {
    setup() {
        // Add any reactive variables here
    },
    data() {
        return {
            aboutImage: About1,
            logo: logo,
            folio1: folio1,
            folio2: folio2,
            folio3: folio3,
        };
    },
};
</script>

<style scoped>
/* Add any custom styles here */
</style>
