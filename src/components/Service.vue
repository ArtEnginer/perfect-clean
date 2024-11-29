<template>
    <section class="py-2 h-auto lg:h-screen flex items-center">
        <div
            class="container max-w-7xl mx-auto px-4 flex flex-col lg:flex-row items-center justify-center space-y-2 lg:space-y-0">
            <div class="w-full lg:w-1/2 text-start mb-10 lg:mb-0">
                <h2 class="text-md sm:text-lg font-semibold text-gray-500">Our Cleaning Services</h2>
                <p class="mt-4 text-2xl sm:text-3xl md:text-4xl text-gray-800 font-bold leading-snug">
                    Keeping your space <br /> fresh and spotless <br /> with professional cleaning
                </p>
                <div class="mt-10 space-y-2">
                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                            <Bolt class="text-blue-600 w-5 h-5" />
                        </div>
                        <div class="flex flex-col text-left">
                            <h3 class="text-md sm:text-lg font-bold text-gray-800 mb-2">Reliable Cleaning Solutions</h3>
                            <p class="text-sm sm:text-base">Dependable cleaning services tailored to your needs.</p>
                        </div>
                    </div>

                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                            <Globe class="text-blue-600 w-5 h-5" />
                        </div>
                        <div class="flex flex-col text-left">
                            <h3 class="text-md sm:text-lg font-bold text-gray-800 mb-2">Eco-Friendly Practices</h3>
                            <p class="text-sm sm:text-base">We use eco-friendly products to ensure a healthier
                                environment.</p>
                        </div>
                    </div>

                    <div class="flex items-start space-x-4">
                        <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                            <Shield class="text-blue-600 w-5 h-5" />
                        </div>
                        <div class="flex flex-col text-left">
                            <h3 class="text-md sm:text-lg font-bold text-gray-800 mb-2">Professional & Safe</h3>
                            <p class="text-sm sm:text-base">Highly trained cleaners for your peace of mind and safety.
                            </p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="w-full lg:w-9/12 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
                <div
                    class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
                    <figure class="relative h-60">
                        <img :src="cs2" alt="Residential Cleaning" class="w-full h-full object-cover" />
                        <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent"></div>
                        <div
                            class="absolute flex bottom-4 left-4 text-white bg-white bg-opacity-20 border border-neutral-500 backdrop-blur-sm px-3 py-1 rounded-3xl items-center font-semibold">
                            Residential Cleaning
                            <MoveUpRight size="13" class="ml-2" />
                        </div>
                    </figure>
                    <div class="card-body p-5">
                        <p class="text-sm sm:text-base leading-snug">Thorough cleaning for your home, ensuring comfort
                            and cleanliness.</p>
                    </div>
                </div>

                <div
                    class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
                    <figure class="relative h-60">
                        <img :src="cs3" alt="Office Cleaning" class="w-full h-full object-cover" />
                        <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent"></div>
                        <div
                            class="absolute flex bottom-4 left-4 text-white bg-white bg-opacity-20 border border-neutral-500 backdrop-blur-sm px-3 py-1 rounded-3xl items-center font-semibold">
                            Office Cleaning
                            <MoveUpRight size="13" class="ml-2" />
                        </div>
                    </figure>
                    <div class="card-body p-5">
                        <p class="text-sm sm:text-base leading-snug">Keep your office space clean and organized for a
                            productive work environment.</p>
                    </div>
                </div>

                <div
                    class="card bg-base-100 shadow-lg rounded-3xl overflow-hidden hover:shadow-xl transition-shadow duration-300">
                    <figure class="relative h-60">
                        <img :src="cs4" alt="Commercial Cleaning" class="w-full h-full object-cover" />
                        <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent"></div>
                        <div
                            class="absolute flex bottom-4 left-4 text-white bg-white bg-opacity-20 border border-neutral-500 backdrop-blur-sm px-3 py-1 rounded-3xl items-center font-semibold">
                            Commercial Cleaning
                            <MoveUpRight size="13" class="ml-2" />
                        </div>
                    </figure>
                    <div class="card-body p-5">
                        <p class="text-sm sm:text-base leading-snug">Comprehensive cleaning solutions for businesses of
                            all sizes.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import { Bolt, Globe, Shield, MoveUpRight } from "lucide-vue-next";
import cs2 from "../assets/img/cs-2.png";
import cs3 from "../assets/img/cs-3.png";
import cs4 from "../assets/img/cs-4.png";

export default {
    components: {
        Bolt,
        Globe,
        Shield,
        MoveUpRight
    },
    data() {
        return {
            cs2: cs2,
            cs3: cs3,
            cs4: cs4
        };
    }
};
</script>

<style scoped>
/* Add any custom styles here */
</style>
