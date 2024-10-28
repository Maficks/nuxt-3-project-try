<template>
  <NuxtLayout>
    <div class="centreDiv">
      <NuxtPage />
      <h1>КРАСИВЫЙ ТЕКСТ))</h1>
    </div>
  </NuxtLayout>
</template>

<style scoped>
* {
  font-family: "Montserrat", sans-serif;
}
.centreDiv {
  position: relative;
  height: 93.6vh;
}
.centreDiv h1 {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%);
}
</style>
<script setup lang="ts"></script>
