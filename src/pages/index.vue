<script setup>
import noImage from "@/assets/photo-1588440691140-09155c1be58a.avif"
import homeSVG from "@/assets/home.svg"
</script>
<template>
    <section class=" p-3">
        <div class="container mx-auto">
            <div class="p-10 grid gap-3">
                <div class="grid grid-cols-2 grid-flow-col gap-3">
                    <div class="col-span-1">

                        <div class="grid gap-3 h-full">
                            <div class="rounded-xl overflow-hidden flex justify-between items-center p-1 px-5 bg-[#1e1b1e]">
                                <svg width="40" height="40" viewBox="0 0 48 48" id="Layer_2" data-name="Layer 2">
                                    <path class="cls-1" stroke="#fff" fill="#fff"
                                        d="M42.63,21.85,25.94,7.64a3,3,0,0,0-3.88,0L5.37,21.85A2.45,2.45,0,0,0,7,26.17H9.09V39.45a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V34.59a4.3,4.3,0,1,1,8.6,0v4.86a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V26.17H41A2.45,2.45,0,0,0,42.63,21.85ZM24,28.3A4.3,4.3,0,1,1,28.3,24,4.31,4.31,0,0,1,24,28.3Z" />
                                </svg>
                                <!-- <p>Lorem ipsum dolor</p> -->
                            </div>
                            <div class="grid grid-cols-2 grid-flow-col gap-3">
                                <div class="grid gap-3">
                                    <div
                                        class="rounded-xl overflow-hidden flex justify-between items-center p-2 px-5 bg-[#1e1b1e]">
                                        <p>نام :</p>
                                        <p>محمد مهدوی</p>
                                    </div>
                                    <div class="rounded-xl overflow-hidden">
                                        <div
                                            class="overflow-hidden flex justify-between items-center p-2 px-5 bg-[#1e1b1e]">
                                            <p>Lorem ipsum dolor</p>
                                            <p>Lorem</p>
                                        </div>
                                        <img :src="noImage" alt="noImage" class="aspect-square object-cover">
                                    </div>
                                    <div
                                        class="rounded-xl overflow-hidden flex justify-between items-center p-2 px-5 bg-[#1e1b1e]">
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            <svg width="40" height="40" viewBox="0 0 48 48" id="Layer_2"
                                                data-name="Layer 2">
                                                <path class="cls-1" stroke="#fff" fill="#fff"
                                                    d="M42.63,21.85,25.94,7.64a3,3,0,0,0-3.88,0L5.37,21.85A2.45,2.45,0,0,0,7,26.17H9.09V39.45a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V34.59a4.3,4.3,0,1,1,8.6,0v4.86a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V26.17H41A2.45,2.45,0,0,0,42.63,21.85ZM24,28.3A4.3,4.3,0,1,1,28.3,24,4.31,4.31,0,0,1,24,28.3Z" />
                                            </svg>
                                        </div>
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            <svg width="40" height="40" viewBox="0 0 48 48" id="Layer_2"
                                                data-name="Layer 2">
                                                <path class="cls-1" stroke="#fff" fill="#fff"
                                                    d="M42.63,21.85,25.94,7.64a3,3,0,0,0-3.88,0L5.37,21.85A2.45,2.45,0,0,0,7,26.17H9.09V39.45a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V34.59a4.3,4.3,0,1,1,8.6,0v4.86a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V26.17H41A2.45,2.45,0,0,0,42.63,21.85ZM24,28.3A4.3,4.3,0,1,1,28.3,24,4.31,4.31,0,0,1,24,28.3Z" />
                                            </svg>
                                        </div>
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            <svg width="40" height="40" viewBox="0 0 48 48" id="Layer_2"
                                                data-name="Layer 2">
                                                <path class="cls-1" stroke="#fff" fill="#fff"
                                                    d="M42.63,21.85,25.94,7.64a3,3,0,0,0-3.88,0L5.37,21.85A2.45,2.45,0,0,0,7,26.17H9.09V39.45a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V34.59a4.3,4.3,0,1,1,8.6,0v4.86a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V26.17H41A2.45,2.45,0,0,0,42.63,21.85ZM24,28.3A4.3,4.3,0,1,1,28.3,24,4.31,4.31,0,0,1,24,28.3Z" />
                                            </svg>
                                        </div>
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            <svg width="40" height="40" viewBox="0 0 48 48" id="Layer_2"
                                                data-name="Layer 2">
                                                <path class="cls-1" stroke="#fff" fill="#fff"
                                                    d="M42.63,21.85,25.94,7.64a3,3,0,0,0-3.88,0L5.37,21.85A2.45,2.45,0,0,0,7,26.17H9.09V39.45a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V34.59a4.3,4.3,0,1,1,8.6,0v4.86a1.63,1.63,0,0,0,1.63,1.63h7.35a1.63,1.63,0,0,0,1.63-1.63V26.17H41A2.45,2.45,0,0,0,42.63,21.85ZM24,28.3A4.3,4.3,0,1,1,28.3,24,4.31,4.31,0,0,1,24,28.3Z" />
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                                <div class="rounded-xl overflow-hidden">
                                    <img :src="noImage" alt="noImage" class="">
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col-span-1">
                        <div class="grid justify-between gap-3 h-full">
                            <div class="p-5 rounded-xl bg-[#1e1b1e]">
                                <p class="text-[48px]" dir="ltr">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                </p>
                                <button class="bg-purple-500 px-5 p-2 rounded-full">استخدام کنید</button>
                            </div>
                            <div class="grid grid-flow-col grid-cols-3 gap-3">
                                <div
                                    class="col-span-1 rounded-xl overflow-hidden p-3 aspect-square flex justify-center items-center text-center bg-red-500">
                                    <div class="font-bold">
                                        <p class="text-[30px]">+10</p>
                                        <p>پروژه مشترک</p>
                                    </div>
                                </div>
                                <div
                                    class="col-span-1 rounded-xl overflow-hidden p-3 aspect-square flex justify-center items-center text-center bg-yellow-300">
                                    <div class="text-black font-bold">
                                        <p class=" text-[30px]">+5</p>
                                        <p>پروژه تمام شده</p>
                                    </div>
                                </div>
                                <div
                                    class="col-span-1 rounded-xl overflow-hidden p-3 aspect-square flex justify-center items-center text-center bg-green-500">
                                    <div class="font-bold">
                                        <p class="text-[30px]">+1</p>
                                        <p>سابقه فعالیت</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="grid grid-cols-12 grid-flow-col gap-3">
                    <div class="col-span-4">
                        <div class="rounded-xl overflow-hidden p-5 bg-[#1e1b1e] h-full">
                            <div class="grid grid-cols-2 items-center">
                                <p class="text-[24px]"><strong>درباره</strong></p>
                                <p class="text-end text-[18px] font-thin">رزومه</p>
                            </div>
                            <p class="text-justify">
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor repellat molestias
                                aspernatur
                                fugiat ipsa. Esse possimus accusantium corporis consequuntur consequatur inventore error,
                                quam
                                quasi fugit nesciunt maxime, ratione cupiditate? Officia.
                            </p>
                        </div>
                    </div>
                    <div class="col-span-8">
                        <div class="rounded-xl overflow-hidden p-5 bg-[#1e1b1e] h-full">
                            <div class="grid grid-cols-2 items-center pb-3">
                                <p class="text-[24px]"><strong>پورتفولیو</strong></p>
                                <p class="text-end text-[18px] font-thin">مشاهده همه</p>
                            </div>
                            <div class="grid grid-cols-3 grid-flow-col gap-3">
                                <div class="rounded-xl overflow-hidden">
                                    <img :src="noImage" alt="noImage" class="aspect-square object-cover">
                                </div>
                                <div class="rounded-xl overflow-hidden">
                                    <img :src="noImage" alt="noImage" class="aspect-square object-cover">
                                </div>
                                <div class="rounded-xl overflow-hidden relative">
                                    <img :src="noImage" alt="noImage" class="aspect-square object-cover">
                                    <div
                                        class="bg-[#000000b9] absolute top-0 left-0 w-full h-full flex justify-center items-center">
                                        <p>مطالب بیشتر</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>