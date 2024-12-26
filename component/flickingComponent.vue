<template>
  <Flicking
      :plugins="plugins"
      circular
      :options="{ circular: true }"
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
const images = [
  "/images/flicking/arloopa.png",
  "/images/flicking/meluvis.png",
  "/images/flicking/light_clash.png",
  "/images/flicking/ar_trails.png",
  "/images/flicking/art_world.png",
  "/images/flicking/phys_2.png",
  "/images/flicking/immerence.png",
];
const plugins = [new AutoPlay({ duration: 2000, direction: "NEXT", stopOnHover: true })];

</script>

<style scoped>
.flicking-viewport {
  width: 100%;
  overflow: hidden;
  position: relative;
}

.panel-image:hover {
  border: 2px solid #5ABFA4;
}

.plugins-panel {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 10px;
  flex-shrink: 0;
}

.panel-image {
  width: 100%;
  max-width: 400px;
  height: auto;
  transition: border 0.3s ease;
  border: 2px solid transparent;
  user-select: none ;
  user-drag: none;
  -webkit-user-drag: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;

}

@media (max-width: 1024px){
  .panel-image{
     height: 500px;
  }
}
</style>


