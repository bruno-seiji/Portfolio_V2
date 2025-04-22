<script setup>
    const props = defineProps({
        urlimg: String,
        urlsite: String,
        title: String,
        resume: String
    })
</script>

<template>
    <a :href="urlsite">
        <img :src="urlimg" alt="" srcset="">
        <title>{{ title }}</title>
        <p>{{ resume }}</p>
        <div id="tecnologias"></div>
    </a>
    
    

</template>

<style scoped>
    @media (max-width: 450px) {
       a{
            font-size: 1.2rem;

            img{
                width: 100%;
                
            }

            
            p{
                grid-column: 1 / span 2;
            }
        }


    }

    @media (min-width: 1270px) {
       a{
            font-size: 1.5rem;

            
            img{
                grid-row: 1 / span 2;
                justify-self: center;
                width: 70%;
            }


        }

        a:hover {
           background-color: rgb(15, 23, 42,0.5);
            color: rgb(255, 255, 255, 1);
            
            title{
                color: aqua;
            }

    }
}  
    
    a{
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: auto auto;
        text-decoration: none;
        gap: 1rem;
        color: rgb(255, 255, 255, 0.5);

        title{
            display: block;
            width: fit-content;
        }
        

        img{
            
            align-self: center;
            
        }



    }

</style>