<script setup>
    import PJ from "../micro_components/project.vue"
</script>

<template>
    <div id="projects">
        <PJ urlsite="https://chipper-gumdrop-9088d1.netlify.app/" urlimg="../src/assets/img/B2CA.png" title="B2CA - Soluções em Tecnologia" resume="Landpage de uma empresa comercial de solu;óes em T.I, desenvolvido utilizando tecnologias como Vue.js, afim de estudar tal tecnologia."></PJ>
        <PJ urlsite="https://projeto-car-wash.vercel.app" urlimg="../src/assets/img/carwash.png" title="Mobile Detaling " resume="LandPage de uma empresa lavagem de carros, desenvolvida para estudo de tecnologias como TailWindCss, Html e CSS" ></PJ>
        <PJ urlsite="https://projeto-lux-chaffeur-sass.vercel.app" urlimg="../src/assets/img/luxChaffeur.png" title="Projeto LuxChaffeur" resume="LandPage de empresa de motorista particular, desenvolvida com Html, Css,  Javascript e préprocessador SASS."></PJ>
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