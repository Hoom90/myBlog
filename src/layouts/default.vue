<script setup>
import headerComp from './headerComp.vue';
import footerComp from './footerComp.vue';
</script>
<template>
  <!-- <headerComp /> -->
  <div class="container h-100 min-h-[calc(100vh-56px)]">
    <router-view />
  </div>
  <footerComp />
</template>