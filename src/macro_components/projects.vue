<script setup>
    import PJ from "../micro_components/project.vue"
</script>

<template>
    <div>
        <PJ urlimg="../src/assets/img/B2CA.png" title="B2CA - Soluções em Tecnologia" resume="Landpage de uma empresa comercial de solu;óes em T.I, desenvolvido utilizando tecnologias como Vue.js, afim de estudar tal tecnologia."></PJ>
        <PJ urlimg="../src/assets/img/carwash.png" title="Mobile Detaling " resume="LandPage de uma empresa lavagem de carros, desenvolvida para estudo de tecnologias como TailWindCss, Html e CSS" ></PJ>
        <PJ></PJ>
    </div>


</template>


<style scoped>
    div{
        margin-top: 2rem;
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }
</style>