<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue';
import icon from '@assets/icons/logo-1.svg';
import json from '../package.json';
console.log(json);
</script>

<template>
  <img alt="Vue logo" src="@assets/logo.png" />
  <img alt="Vue logo" :src="icon" />
  {{ json }}
  <!-- <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" /> -->
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background: url(@assets/);
}
</style>
