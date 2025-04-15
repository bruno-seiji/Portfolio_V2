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
        color: white ;
        gap: 0.8rem;
        font-size: 1.3rem;

        #work_lenght{
            grid-row: 1 / span 2 ;
            margin-right: 1rem;
            opacity: 0.5;
            width: 13rem;
        }

        #title{}

        #resume{
            opacity: 0.5;
        }

    }

</style>