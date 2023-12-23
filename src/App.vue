<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Nav from './components/navbar/navbarComponent.vue'
import Main from './components/main.vue'
</script>
<template>
  <Nav></Nav>
  <Main></Main>
  <RouterView/>
</template>
