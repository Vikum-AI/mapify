<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar.vue";
import MapCanvas from "./components/MapCanvas.vue";
</script>

<template>
  <nav>
    <NavBar class="navbar" />
  </nav>

  <MapCanvas />

  <RouterView />
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.navbar {
}
</style>
