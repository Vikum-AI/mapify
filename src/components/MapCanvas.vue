<script setup lang="ts">
import { MapboxMap } from "@studiometa/vue-mapbox-gl";
</script>

<template>
  <MapboxMap
    style="height: 100vh; width: 100vw"
    access-token="pk.eyJ1Ijoic2VoYW5kdWsiLCJhIjoiY2w3cmtzOGptMGdiNTN2bnZxemNmajNzaCJ9.ZmuUXZWARzCl1SybKVojww"
    map-style="mapbox://styles/mapbox/streets-v11"
    :center="[0, 0]"
    :zoom="1"
  />
</template>

<style></style>
