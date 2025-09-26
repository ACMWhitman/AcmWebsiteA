<script setup>
defineProps(['text'])
</script>
<template>
    <div class="templatebutton">{{ text }}</div>
</template>
<style>
.templatebutton{
    padding:7px;
    cursor:pointer;
}
.templatebutton:hover{
    background:rgba(0, 0, 0, 0.26);
}
</style>