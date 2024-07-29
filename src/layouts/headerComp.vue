<script setup>
import homeSVG from "@/assets/home.svg"
</script>
<template>
    <div class="absolute right-0 top-0 w-screen">
        <div class="p-3 bg-red-500 flex">
            <div>
                <img :src="homeSVG" @click="handleSidebar">
            </div>
            <ul class="flex gap-5 transition-all ease-in-out opacity-1">
                <li class="bg-white rounded">
                    <img :src="homeSVG">
                </li>
                <li class="bg-white rounded">
                    <img :src="homeSVG">
                </li>
                <li class="bg-white rounded">
                    <img :src="homeSVG">
                </li>
            </ul>
        </div>
    </div>
</template>