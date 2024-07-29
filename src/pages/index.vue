<script setup>
import noImage from "@/assets/photo-1588440691140-09155c1be58a.avif"
import homeSVG from "@/assets/home.svg"
</script>
<template>
    <section class=" p-3">
        <div class="container mx-auto">
            <div class="p-10">
                <div class="grid grid-cols-12 grid-flow-col gap-5">
                    <div class="col-span-4">
                        <div class="grid gap-5">
                            <div
                                class="border rounded-xl overflow-hidden flex justify-between items-center p-3 bg-white text-slate-900">
                                <img :src="homeSVG" alt="">
                                <p>Lorem ipsum dolor</p>
                            </div>
                            <div class="border rounded-xl overflow-hidden">
                                <img :src="noImage" alt="noImage" class="">
                            </div>
                        </div>
                    </div>
                    <div class="col-span-8">
                        <div class="grid gap-5">
                            <div class="p-3 border rounded-xl">
                                <p>Lorem ipsum dolor .</p>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat dolorem distinctio,
                                    quasi
                                    repellendus natus neque ducimus quisquam excepturi fugiat facere cupiditate aliquid
                                    minus
                                    placeat
                                    reiciendis, facilis corporis, inventore vero doloremque.</p>
                            </div>
                            <div class="grid grid-flow-col gap-5">
                                <div
                                    class="border rounded-xl overflow-hidden p-3 h-40 flex justify-center items-center bg-red-500">
                                    10+
                                </div>
                                <div
                                    class="border rounded-xl overflow-hidden p-3 h-40 flex justify-center items-center bg-yellow-300">
                                    5+
                                </div>
                                <div
                                    class="border rounded-xl overflow-hidden p-3 h-40 flex justify-center items-center bg-green-500">
                                    1+
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    index
</template>