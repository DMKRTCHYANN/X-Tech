<template>
  <div class="calendar-wrapper">
    <VCalendar :attributes="attrs" />
  </div>
</template>

<script setup>
import { ref } from 'vue';

const attrs = ref([
  {
    key: 'today',
    highlight: true,
    dates: new Date(),
  },
]);
</script>

<style scoped>
.calendar-wrapper {
  margin: 0 auto;
  padding: 20px;
  background-color: rgb(19, 34, 47);
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}



</style>
