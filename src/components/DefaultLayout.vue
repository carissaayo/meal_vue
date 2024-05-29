<script setup>
import Navbar from "./Navbar.vue";
</script>

<template>
  <div class="bg-gray-100 h-full">
    <Navbar />
    <main>
      <RouterView />
    </main>
  </div>
</template>
