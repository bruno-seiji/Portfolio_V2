<script setup>
    import PJ from "../micro_components/project.vue"
    import b2ca from '../assets/img/B2CA.png'
    import carwash from '../assets/img/carwash.png'
    import lux from '../assets/img/luxChaffeur.png'
    import barba from '../assets/img/barbearia.png'
</script>

<template>
    <div id="projects">
        <PJ urlsite="https://chipper-gumdrop-9088d1.netlify.app/" :urlimg="b2ca" title="B2CA - Soluções em Tecnologia" resume="Landpage de uma empresa comercial de solu;óes em T.I, desenvolvido utilizando tecnologias como Vue.js, afim de estudar tal tecnologia."></PJ>
        <PJ urlsite="https://projeto-car-wash.vercel.app" :urlimg="carwash" title="Mobile Detaling " resume="LandPage de uma empresa lavagem de carros, desenvolvida para estudo de tecnologias como TailWindCss, Html e CSS" ></PJ>
        <PJ urlsite="https://projeto-lux-chaffeur-sass.vercel.app" :urlimg="lux" title="Projeto LuxChaffeur" resume="LandPage de empresa de motorista particular, desenvolvida com Html, Css,  Javascript e préprocessador SASS."></PJ>
        <PJ urlsite="https://barbearia-alura-bscc.netlify.app" :urlimg="barba" title="Projeto Barbearia" resume="LandPage de uma babrbearia, desenvolvida com Html, Css,  Javascript."></PJ>
    </div>


</template>


<style scoped>

@media (min-width: 1270px) {

    div{
        margin-top: 8rem;
    }
}

div{
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }
</style>
