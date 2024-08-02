<script setup>
import headerComp from './headerComp.vue';
import footerComp from './footerComp.vue';
</script>
<template>
  <!-- <headerComp /> -->
  <div class="h-100 w-100 mx-auto min-h-[calc(100vh-56px)] bg-[#0f0f0f] text-white">
    <router-view />
  </div>
  <footerComp />
</template>