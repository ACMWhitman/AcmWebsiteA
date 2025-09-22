<script setup>
import Headbar from '../components/Headbar.vue';
import { createRouter } from 'vue-router';

createRouter({
  routes:{
    
  }
})

</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <Headbar />
    <RouterView/>
  </div>
</template>
