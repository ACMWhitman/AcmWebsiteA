<script setup>
import HeadbarButton from './HeadbarButton.vue'
</script>
<template>
    <div class="headbar">
        <HeadbarButton text="test"></HeadbarButton>
        <HeadbarButton text="test2"></HeadbarButton>
    </div>
</template>
<style>
.headbar {
    display: flex;
    flex-flow: row nowrap;
}
</style>