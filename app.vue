<template>
  <body>
    <NuxtLayout>
      <div class="centreDiv">
        <h1><NuxtPage /></h1>
      </div>
    </NuxtLayout>
  </body>
</template>

<style scoped>
* {
  font-family: "Montserrat", sans-serif;
}
body {
  margin: 0;
  padding: 0;
  position: relative;
  background-color: powderblue;
}
.centreDiv {
  position: relative;
  height: 93.6vh;
  perspective: 500px;
}
.centreDiv h1 {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%);
  margin-top: 0;
  margin-bottom: 0;
}
NuxtLayout {
  position: absolute;
  top: 100px;
}
</style>
<script setup lang="ts"></script>
