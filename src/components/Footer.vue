<template>
    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto py-12 px-4">
            <div class="flex flex-col lg:flex-row space-y-4 lg:space-y-0 lg:space-x-4">
                <div class="flex flex-col items-center">
                    <img :src="logo" alt="Logo" class="w-24 h-24" />
                    <p class="mt-4 text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo expedita
                        voluptas culpa sapiente alias molestiae. Numquam corrupti in laborum sed rerum et corporis.</p>
                    <div class="mt-4 flex space-x-4">
                        <a href="mailto:anggaegae@gmail.com" class="text-white">
                            <Mail class="w-6 h-6" />
                        </a>
                        <a href="https://www.linkedin.com/in/anggaegae/" target="_blank" class="text-white">
                            <Linkedin class="w-6 h-6" />
                        </a>
                        <a href="https://www.instagram.com/anggaegae/" target="_blank" class="text-white">
                            <Instagram class="w-6 h-6" />
                        </a>
                    </div>
                </div>
                <div class="flex flex-col">
                    <h3 class="text-lg font-semibold">Quick Links</h3>
                    <ul class="mt-4 space-y-2">
                        <li>
                            <a href="#" class="hover:text-blue-500">Home</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">About</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Services</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Gallery</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Contact</a>
                        </li>
                    </ul>
                </div>
                <div class="flex flex-col">
                    <h3 class="text-lg font-semibold">Quick Links</h3>
                    <ul class="mt-4 space-y-2">
                        <li>
                            <a href="#" class="hover:text-blue-500">Home</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">About</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Services</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Gallery</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Contact</a>
                        </li>
                    </ul>

                </div>
                <div class="flex flex-col">
                    <h3 class="text-lg font-semibold">Quick Links</h3>
                    <ul class="mt-4 space-y-2">
                        <li>
                            <a href="#" class="hover:text-blue-500">Home</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">About</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Services</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Gallery</a>
                        </li>
                        <li>
                            <a href="#" class="hover:text-blue-500">Contact</a>
                        </li>
                    </ul>

                </div>
            </div>
        </div>
    </footer>
</template>

<script>
import { Mail, Linkedin, Instagram } from "lucide-vue-next"; import logo from "../assets/logo.png"; export default {
    name: "Footer", components: { Mail, Linkedin, Instagram }, data() {
        return {
            logo: logo
        };
    }
}; </script>

<style scoped>
/* You can add any specific styles for this component here */
</style>
