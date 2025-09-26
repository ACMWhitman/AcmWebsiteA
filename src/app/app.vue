<script setup>
import Headbar from './components/Headbar.vue'
import './brand.css'
</script>

<template>
  <div>
    <Headbar />
    <NuxtRouteAnnouncer />
    <NuxtPage />
  </div>
</template>
<style>

body, html{
  margin:0px;
  padding:none;
}


html{
  font-family: roboto;
}

</style>