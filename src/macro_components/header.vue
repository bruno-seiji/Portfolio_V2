<script setup>
    function scrolltotop() {
        
        window.scrollTo({top: 0,  behavior: 'smooth'});
        
    }

</script>

<template>
    <header>
        <h1>Bruno Seiji</h1>
        <p>Desenvolvedor Front-end</p>
        <p>Criação de sites inclusivos e responsivos para uma melhor experiencia web</p>
        <ul id="guide">
            <li @click="scrolltotop">Sobre</li>
            <li><a href="#experiences">Experiencias</a></li>
            <li><a href=""></a>Projetos</li>
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
            font-size: 1.5rem;
            color: rgb(255,255,255,0.5);
            width: 60%;
            text-align: justify;
        }

        #guide{
            display: flex;
            flex-direction: column;
            gap: 1rem;
            margin-top: 5rem;
            width: fit-content;

            li{
                font-size: 1.5rem;
                width: fit-content;  
                cursor: pointer;

                a{
                    text-decoration: none;
                    color: white;
                    width: fit-content;    
                }
            }

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

