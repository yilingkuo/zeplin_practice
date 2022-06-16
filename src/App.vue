<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
import Home from './view/Home.vue'
</script>

<template>
  <div class="flex items-center justify-center h-screen bg-dunes">
    <Home msg="Hello Vue 3 + Vite" />
  </div>
</template>

<style>
/* .container {
  height: 100vh;
  width: 100vw
} */

#app {
  background-image: url("./assets/background image.png");
  background-size: 1920px 1080px;
  background-repeat: no-repeat;
  background-position: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
