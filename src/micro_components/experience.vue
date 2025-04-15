<script setup>
    const props = defineProps({
        wlenght: String,
        title: String,
        resume: String
    })
</script>

<template>
  <div>
    <p id="work_lenght">{{ wlenght }}</p>
    <p id="title">{{ title }}</p>
    <p id="resume">{{ resume }}</p>
  </div>

</template>

<style scoped>
    div{
        display: grid;
        grid-template-columns: auto auto;
        grid-template-rows: repeat(2, auto) ;

    }

</style>