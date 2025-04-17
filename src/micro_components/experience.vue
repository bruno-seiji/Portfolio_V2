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
      @media (min-width: 1270px) {

        div{
            display: flex;
            flex-direction: column;
            gap: 1rem;
            
            p{
                font-weight: 400;
                font-size: 1.2rem;
                text-align: justify;
            }
        }
      }


    @media (max-width: 450px) {
        div {
            display: flex;
            flex-direction: column;
            

            p:first-of-type {
                margin-top: 1rem;
            }

            p:last-of-type{
                margin-bottom: 2rem;
            }
                      
           p{ 
                width: 90vw;
                overflow-x: auto;
                word-break: break-word;
                box-sizing: border-box;
                text-align: justify;
                font-size: 1.2rem;
                color: rgb(255, 255, 255, 0.5);
                line-height: 1.5rem;
            }

            #title{
                color: rgb(255, 255, 255, 1); 
            }
        }
    }

</style>