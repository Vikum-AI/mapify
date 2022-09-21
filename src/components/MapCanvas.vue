<!-- <script lang="ts">
const token =
  "pk.eyJ1Ijoic2VoYW5kdWsiLCJhIjoiY2w3cmtzOGptMGdiNTN2bnZxemNmajNzaCJ9.ZmuUXZWARzCl1SybKVojww";
</script>

<template>
  <mapbox-map
    accessToken="pk.eyJ1Ijoic2VoYW5kdWsiLCJhIjoiY2w3cmtzOGptMGdiNTN2bnZxemNmajNzaCJ9.ZmuUXZWARzCl1SybKVojww"
    mapStyle="light-v10"
  />
</template> -->

<script setup>
import { MapboxMap } from "@studiometa/vue-mapbox-gl";
</script>

<template>
  <!-- <div class="map-cont">
    <MapboxMap
      access-token="pk.eyJ1Ijoic2VoYW5kdWsiLCJhIjoiY2w3cmtzOGptMGdiNTN2bnZxemNmajNzaCJ9.ZmuUXZWARzCl1SybKVojww"
      @mb-created="(mapboxInstance: any) => (map = mapboxInstance)"
    />
  </div> -->
  <MapboxMap
    style="height: 400px; width: 400px"
    access-token="pk.eyJ1Ijoic2VoYW5kdWsiLCJhIjoiY2w3cmtzOGptMGdiNTN2bnZxemNmajNzaCJ9.ZmuUXZWARzCl1SybKVojww"
    map-style="mapbox://styles/mapbox/streets-v11"
    :center="[0, 0]"
    :zoom="1"
  />
</template>

<style>
.map-cont {
  background-color: red;
  width: 50vw;
  height: 50vh;
}
</style>
