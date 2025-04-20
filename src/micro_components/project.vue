<script setup>
    const props = defineProps({
        urlimg: String,
        title: String,
        resume: String
    })
</script>

<template>
    <a href="https://chipper-gumdrop-9088d1.netlify.app/">
        <img :src="urlimg" alt="" srcset="">
        <title>{{ title }}</title>
        <p>{{ resume }}</p>
        <div id="tecnologias"></div>
    </a>
    
    

</template>

<style scoped>
    a{
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: auto auto;
        text-decoration: none;
        color: white;
        gap: 1rem;

        img{
            
            align-self: center;
            width: auto;
        }

        p{
            grid-column: 1 / span 2;
        }


    }

</style>