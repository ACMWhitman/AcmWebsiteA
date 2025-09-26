<script setup>
let props = defineProps(['text','to'])
let boi = props.to ?? ''
</script>
<template>
    <a :href="boi"><div class="templatebutton">{{ text }}</div></a>
</template>
<style>
.templatebutton{
    padding:7px;
    cursor:pointer;
}
.templatebutton:hover{
    background:rgba(0, 0, 0, 0.26);
}
a {
    text-decoration: unset;
    color: unset;
}
</style>