<script setup>
import HeadbarButton from './HeadbarButton.vue'
</script>
<template>
    <div class="headbar">
        <HeadbarButton text="Home"></HeadbarButton>
        <HeadbarButton text="About"></HeadbarButton>
        <HeadbarButton text="Blog"></HeadbarButton>
    </div>
</template>
<style>
.headbar {
    display: flex;
    flex-flow: row nowrap;
    align-items: start;
    justify-content: center;
}
</style>