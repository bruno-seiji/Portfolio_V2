<script setup></script>


<template>
    <div id="about">
        <p>
        Sou <span class="destaque">Engenheiro Elétrico</span> e atualmente estou cursando <span class="destaque">Análise e Desenvolvimento de Sistemas</span>, com foco em <span class="destaque">desenvolvimento web</span>. Estou estudando <span class="destaque">Vue.js e React</span> (ambos em processo de aprendizado), e me familiarizando com tecnologias como <span class="destaque">HTML, CSS, JavaScript, Tailwind CSS e SASS</span>.
        </p>

        <p>
            Minha jornada na tecnologia é impulsionada pela busca constante por inovação e eficiência, com o objetivo de criar interfaces modernas e responsivas. Estou em busca de oportunidades para atuar na área de desenvolvimento web e continuar evoluindo como <span class="destaque">desenvolvedor front-end</span>.
        </p>

        <p>
            Minhas principais habilidades incluem: <span class="destaque">HTML, CSS, JavaScript, Vue.js (em aprendizado), React (em aprendizado), Tailwind CSS, SASS</span> e a criação de interfaces responsivas e bem estruturadas.
        </p>
    
        <p>
            Estou aberto a <span class="destaque">conexões, colaborações e oportunidades</span> na área de desenvolvimento web. Vamos trocar experiências e crescer juntos nesse universo tech!
        </p>
    </div>
</template>


<style scoped>
    @media (min-width: 1270px) {

        div{
            display: flex;
            flex-direction: column;
            gap: 1rem;
            font-size: 1.5rem;

            p{
                font-weight: 400;
               
                text-align: justify;
                color: rgb(255, 255, 255, 0.5);
                line-height: 2rem;
                

                span{
                    color: rgb(255, 255, 255, 1);
                }
            
            
            }
        }



}

    @media (max-width: 450px) {
        div {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            margin-bottom: 8rem;
            
            
           
           p{ 
                width: 90vw;
                overflow-x: auto;
                word-break: break-word;
                padding: 0.3rem;
                box-sizing: border-box;
                text-align: justify;
                font-size: 1.2rem;
                color: rgb(255, 255, 255, 0.5);
                line-height: 1.5rem;
                

                span{
                    color: rgb(255, 255, 255, 1);
                }
            }
        }

    }

    
</style>