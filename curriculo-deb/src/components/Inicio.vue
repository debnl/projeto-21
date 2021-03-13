<template>
    <div class="all-it">
        <h1 class="bem-vinde"> Seja muito bem vinde!</h1>

        <div class="capsula-about">
            <p class="p-about"> 
                Tudo bem? Eu sou a Déborah, tenho 21 anos, sou formada em ADS, trabalho atualmente como Analista de Testes e sou apaixonada por front-end :)
            </p>
            <img src="https://i.postimg.cc/W4NKyn1B/Whats-App-Image-2021-03-12-at-12-40-33.jpg"
            class="eu-icon" alt="icon em desenho de deb">
        </div> 

        <div class="language">
            <div class="capsula-language">
                <ul>
                    <li>br</li>
                    <li>en</li>
                    <li>fr</li>
                </ul>
            </div>
        </div>

        <div class="cards">
            <div class="card-soft">
                <h2>soft skills</h2>
                <ul>
                    <li>paciência</li>
                    <li>fast learner</li>
                    <li>comunicação</li>
                    <li>organização</li>
                    <li>criatividade</li>
                </ul>
            </div>
             <div class="card-hard">
                <h2>hard skills</h2>
                <ul>
                    <li>inglês avançado</li>
                    <li>francês básico</li>
                    <li>git/github</li>
                    <li>técnicas bdd</li>
                    <li>técnicas de teste</li>
                </ul>
            </div>
             <div class="card-automacao">
                <h2>automação</h2>
                <ul>
                    <li><img class="avatar" src="https://i.postimg.cc/CxkS0mYd/ruby.png"></li>
                    <li><img class="avatar" src="https://i.postimg.cc/yx88Y9jt/capybara.png"></li>
                    <li><img class="avatar" src="https://i.postimg.cc/sXVVwSkx/icons8-selenium.png"></li>
                    <li><img class="avatar" src="https://i.postimg.cc/CKpMn9Jj/icons8-jenkins.png"></li>
                </ul>
            </div>
             <div class="card-front">
                <h2>front-end</h2>
                <ul>
                    <li><img class="avatar" src="https://i.postimg.cc/BQyn4jK7/icons8-html-5.png"></li>
                    <li><img class="avatar" src="https://i.postimg.cc/mkp2cD6D/icons8-css3.png"></li>
                    <li><img class="avatar" src="https://i.postimg.cc/DwXyZ7Qv/icons8-javascript.png"></li>
                    <li><img class="avatar" src="https://i.postimg.cc/9MJcS02p/icons8-visual-studio.png"></li>
                </ul>
            </div>
        </div>
    </div>

    
</template>

<script>
export default {
    name: 'Inicio'
}
</script>

<style scoped>

.avatar{
    width: 40px;
}

.eu-icon {
    width: 150px;
    border-radius: 50%;
}

.bem-vinde{
    display: flex;
    align-items: flex-start;
    margin-left: 150px;
}

.capsula-about{
    display: flex;
    grid-column: 1 / span 2;
    max-width: 500px;
    align-items: initial;
    align-content: center;
    padding: 1%;
    margin-left: 148px;
    background-color: #FFD9D9;
    border-radius: 20px;
}

.p-about {
    margin: 10 0 0 0px; 
    padding: 17px;
}

</style>