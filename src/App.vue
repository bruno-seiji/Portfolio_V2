<script setup>
  import Theheader from "../src/macro_components/header.vue"
  import Theabout from "../src/macro_components/about.vue"
</script>

<template>
  <div id="main">  
    <Theheader></Theheader>
    <div id="infs">
      <Theabout></Theabout>
    </div>

  </div>
  

</template>

<style scoped>

  #main{
    width: 100vw;
    height: 100vh;
    background-color: rgb(15, 23, 42);
    display: flex;
    overflow: hidden;
    padding: 1rem;
    box-sizing: border-box;
    
  }

  #infs{
    width: 50%;
    height: 95%;
    border: solid red ;
    position: absolute;
    right: 0;
    overflow-y: scroll;
  }
</style>
