<template>
  <Flicking
      :plugins="plugins"
      :options="{ circular: true  }"
      class="flicking-viewport"
      style="width: 100%; overflow: hidden; position: relative;"
  >
    <div class="plugins-panel" v-for="(image, index) in images" :key="index">
      <img class="panel-image" :src="image" alt="Flicking Image" />
    </div>
  </Flicking>
</template>

<script setup>
import {AutoPlay} from "@egjs/flicking-plugins";
import Flicking from "@egjs/vue3-flicking";
import {tryUseNuxtApp} from "#app";
const images = [
  "/images/navbar/arloopa.png",
  "/images/navbar/ar_trails.png",
  "/images/navbar/art_world.png",
  "/images/navbar/imerence.png",
  "/images/navbar/light_clash.png",
  "/images/navbar/meluvis.png",
  "/images/navbar/phys.png",
];
const plugins = [new AutoPlay({ duration: 2000, direction: "NEXT", stopOnHover: true })];

</script>

<style scoped>
.flicking-viewport {
  width: 100%;
  overflow: hidden;
  position: relative;
}

.plugins-panel {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 100px;
  flex-shrink: 0;
}

.panel-image {
  width: 100%;
  max-width: 400px;
  height: auto;
  transition: border 0.3s ease;
  border: 2px solid transparent;
  user-select: none ;
  -webkit-user-drag: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
}

@media (max-width: 1024px){
  .panel-image{
    height: 40px;
  }
}
</style>
