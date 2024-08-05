<script setup>
import noImage from "@/assets/photo-1588440691140-09155c1be58a.avif"
import emailIcon from "@/assets/email.svg"
import githubIcon from "@/assets/github.svg"
import linkedinIcon from "@/assets/linkedin.svg"
const burgerIcon = ref()
const state = reactive({
    sidebar: false,
})
</script>
<template>
    <section class=" p-3">
        <div class="container mx-auto">
            <div class="p-10 grid gap-3">
                <div class="grid grid-cols-2 grid-flow-col gap-3">
                    <div class="col-span-1">
                        <div class="grid justify-between gap-3 h-full">
                            <div class="p-5 rounded-xl bg-[#1e1b1e]">
                                <p class="text-[48px]">کسب و کار خودت رو وسعت بده!</p>
                                <p class="p-3">پشت یه کسب و کار خوب یه تیم خوبه!</p>
                                <div class="flex justify-end">
                                    <button class="bg-purple-500 px-5 p-2 rounded-full">شروع همکاری جدید</button>
                                </div>
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
                                        <p>سال سابقه فعالیت</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col-span-1">

                        <div class="grid gap-3 h-full">

                            <div ref="burgerIcon"
                                class="rounded-xl overflow-hidden p-2 px-5 bg-[#1e1b1e] flex items-center justify-end gap-1"
                                @click="state.sidebar = !state.sidebar">
                                <div class="bg-[#272427] p-1 rounded-full w-10 h-10"></div>
                            </div>

                            <div class="grid grid-cols-2 grid-flow-col gap-3">
                                <div class="rounded-xl overflow-hidden col-span-1">
                                    <img :src="noImage" alt="noImage" class="">
                                </div>
                                <div class="grid gap-3 col-span-1">
                                    <div
                                        class="rounded-xl overflow-hidden flex justify-between items-center p-2 px-5 bg-[#1e1b1e]">
                                        <p>نام :</p>
                                        <p>محمد مهدوی</p>
                                    </div>
                                    <div class="rounded-xl overflow-hidden">
                                        <div
                                            class="overflow-hidden flex justify-between items-center p-2 px-5 bg-[#1e1b1e]">
                                            <p>محل سکونت:</p>
                                            <p>قم</p>
                                        </div>
                                        <iframe
                                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d209962.38776323502!2d50.68725261905887!3d34.688471373266324!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3f93bb6eb88ce195%3A0xcc35bec1c2604470!2sQom%2C%20Qom%20Province%2C%20Iran!5e0!3m2!1sen!2s!4v1722888117333!5m2!1sen!2s"
                                            class="aspect-square w-full h-full" allowfullscreen="" loading="lazy"
                                            referrerpolicy="no-referrer-when-downgrade"></iframe>
                                    </div>
                                    <div
                                        class="rounded-xl overflow-hidden flex justify-between items-center p-2 px-5 bg-[#1e1b1e]">
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            <img :src="github">
                                        </div>
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            linkedin
                                        </div>
                                        <!-- <div class="bg-[#272427] p-1 rounded-full">
                                            telegram
                                        </div> -->
                                        <div class="bg-[#272427] p-1 rounded-full">
                                            email
                                        </div>
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
                                <p class="text-[24px]"><strong>نمونه کار ها</strong></p>
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
<style scoped></style>