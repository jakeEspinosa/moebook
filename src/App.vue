<script setup lang="ts">
  import MobileHeader from "@/components/header/MobileHeader.vue";
</script>

<template>
  <div class="wrapper">
    <MobileHeader class="mobile" />
    <nav class="desktop">desktop-nav</nav>
    <main>main</main>
    <footer class="mobile">mobile-footer</footer>
    <footer class="desktop">desktop-footer</footer>
</div>
</template>
