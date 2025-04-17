<script setup>
  import Theheader from "../src/macro_components/header.vue"
  import Theabout from "../src/macro_components/about.vue"
  import Thexp from "../src/macro_components/experiences.vue"
 






</script>

<template>
  <div id="main">  
    <Theheader></Theheader>
    <div id="infs">
      <title>About</title>
      <Theabout></Theabout>
      <title>Experience</title>
      <Thexp></Thexp>
    </div>

  </div>
  

</template>

<style >
  @media (max-width: 450px) {
    #main {
      overflow-y: scroll;
    }

    #infs{
      width: 100vw;
      padding: 1rem;
      box-sizing: border-box;
    }

    title{
      display: block;
      color: white;
      font-weight: 700;
      font-size: 1.5rem;
      margin-top: 1rem;
      margin-bottom: 1rem;

    }
  }

  @media(min-width: 1270px){
    #main {
      width: 1270px;
      margin: auto;
      display: flex;
    }

    #infs{
      width: 50vw;
      padding: 1rem;
      padding-top: 5rem;
      box-sizing: border-box;
      position: absolute;
      right: 0;
    }

    #title{
      color: rgb(255, 255,255,1);

    }

    .container{
      margin-top: 3rem;
      p{
        color: rgb(255, 255,255,0.5);
      }

      #work_lenght{
        padding-top: 2rem;
      }

      
    }
  }





</style>
