<script setup>


</script>

<template>
    <header>
        <h1>Bruno Seiji</h1>
        <p>Desenvolvedor Front-end</p>
        <p>Criação de sites inclusivos e responsivos para uma melhor experiencia web</p>
        <ul id="guide">
            <li>Sobre</li>
            <li>Experiencias</li>
            <li>Projetos</li>
        </ul>
        <ul id="socials">
            <li class="github">
                <a href="https://github.com/bruno-seiji">
                    <img src="../assets/img/github.png" alt="" srcset="">
                </a>
            </li>
            <li class="linkdin">
                <a href="https://br.linkedin.com/in/brunoseiji">
                    <img src="../assets/img/linkedin.png" alt="" srcset="">
            </a></li>
        </ul>
    </header>
</template>

<style scoped>
   

@media (max-width: 450px) {
    header {
        padding: 1rem;
        box-sizing: border-box;
        margin-top: 3rem;
        display: flex;
        flex-direction: column;
        gap: 1.5rem;

        h1{
            font-size: 2.5rem;
            font-weight: 700;
        }

        p:first-of-type {
            font-weight: 700;
            color: rgba(255, 255, 255, 1);
        }

        p{
            font-size: 1.2rem;
            color: rgba(255, 255, 255, 0.5);
        }

        #guide{
            display: none;
        }

        #socials{
            display: flex;
            gap: 1rem;
        }
        
        img{width: 2rem;}
    }
}

@media (min-width: 1270px) {
    header {
        width: 50%;
        height: 100vh;
        justify-self: start;
        display: flex;
        flex-direction: column;
        gap: 1rem;
        padding: 1rem;
        padding-top: 5rem;
        box-sizing: border-box;
        position: fixed;

        h1{
            font-weight: 700;
            font-size: 3rem;
            
        }

        p:first-of-type{
            font-weight: 700;
            color: rgb(255,255,255,1);
            width: 100%;
        }

        p{
            font-size: 1.2rem;
            color: rgb(255,255,255,0.5);
            width: 60%;
            text-align: justify;
        }

        #guide{
            display: flex;
            flex-direction: column;
            gap: 1rem;
            margin-top: 5rem;

         li:hover{
            text-decoration: underline;
         }
        }

        #socials{
            display: flex;
            gap: 1rem;
            margin-top: 15rem;
            
            img{
                width: 2rem;
            }
        }
    }
}
</style>

