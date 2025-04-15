<script setup>

const minhaDiv = document.querySelector('.infs')

function thescroll() {
  minhaDiv.scrollTo({
  top: 200, // scrolla verticalmente 200px
  behavior: 'smooth' // rolagem suave
})
}

</script>

<template>
    <header>
        <h1>Bruno Seiji</h1>
        <p class="plusfont">Desenvolvedor Front-end</p>
        <p>Criação de sites inclusivos e responsivos para uma melhor experiencia web</p>
        <ul id="guide">
            <li>Sobre</li>
            <li @click="thescroll">Experiencias</li>
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
    header{
        color: white;
        gap: 1rem;
        position: fixed;
        display: flex;
        flex-direction: column ;
        padding-top: 10%;
        box-sizing: border-box;
        width: 50%;

        h1{
            font-weight: 700;
            font-size: 4rem;
        }

        p{
            font-weight: 400;
            font-size: 1.2rem;
            opacity: 0.5;
            width: 60%;
        }

        .plusfont{
            opacity: 1;
        }
    
        li{
            cursor: pointer;
            width: fit-content;

        }

        #guide{
            margin-top: 4rem;
            display: flex;
            flex-direction: column;
            gap: 0.8rem;
            margin-bottom: 2rem;

            li{
                font-size: 1.5rem;
            }

            li:hover{
                text-decoration: underline;
            }
        }

        #socials{

            display: flex;
            gap: 1rem;
            img{
                width: 2rem;
                color: white;
                
            }
        }

}
</style>

