<script setup lang="ts">
  import MobileHeader from "@/components/header/MobileHeader.vue";
  import DesktopHeader from "@/components/header/DesktopHeader.vue";
</script>

<template>
  <div class="wrapper">
    <MobileHeader class="mobile" />
    <DesktopHeader class="desktop" />
    <main>main</main>
    <footer class="mobile">mobile-footer</footer>
    <footer class="desktop">desktop-footer</footer>
</div>
</template>
