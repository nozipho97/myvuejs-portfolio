<template>
    <div>
    <div class="container">
        <h1>Projects</h1>
        <div class="card" style="width: 400px;height:500px;" v-for="person in people">
            <img :src="person.image" class="card-img-top" style="height: 300px;" >
            <div class="card-body">
              <h5 class="card-title">{{person.name}}</h5>
              <p class="card-text">{{person.msg}}</p>
              <a :href="person.netlify" class="btn btn-dark" target="_blank">Netlify</a>
              <a :href="person.github" class="btn btn-dark">Github</a>
            </div>
          </div>
    </div>
    </div>

</template>
<script>
export default {
    data() {
        return {
            people: [
                {
                    name: 'Portfolio',
                    msg: 'A portfolio based on myself, my experiences and the work I did.',
                    image: 'https://i.postimg.cc/ZYVX1VgQ/portfolio.jpg',
                    netlify: 'https://nozipho-portfolio.netlify.app',
                    github:'https://github.com/nozipho97/port-folio.git'
                },
                {
                    name: 'Calculator',
                    msg: 'A normal calculator built with HTML, CSS and JavaScript.',
                    image: 'https://i.postimg.cc/4N4scKCD/calculator.jpg',
                    netlify:'https://nozipho-calculator.netlify.app',
                    github: 'https://github.com/nozipho97/Calculator.git'
                },
                {
                    name: 'Netflix',
                    msg: 'A netflix website built with HTML and CSS.',
                    image: 'https://i.postimg.cc/wvzSdPgC/istockphoto-1126827760-612x612.jpg',
                    netlify: 'https://nozipho-netflix.netlify.app',
                    github:'https://github.com/nozipho97/NetflifClone.git'
                },
                {
                    name: 'E-commerce',
                    msg: 'An e-commerce website built with HTML, CSS, JavaScript',
                    image: 'https://i.postimg.cc/MTbJMw9Z/ecommerce.jpg',
                    netlify: 'https://nozipho-jsproject.netlify.app',
                    github:'https://github.com/nozipho97/JS-Project.git'
                },
                {
                    name: 'Sneaker',
                    msg: 'A basic website on e-commerce built with HTML and CSS.',
                    image: 'https://i.postimg.cc/K8gV3FzX/sneaker.jpg',
                    netlify: 'https://sneaker-mania.netlify.app',
                    github:'https://github.com/nozipho97/sneaker-project.git'
                },
                {
                    name: 'Basic Site',
                    msg: 'Basic site built with HTML and CSS',
                    image: 'https://i.postimg.cc/9FbRdzW6/istockphoto-1047790854-170667a.jpg',
                    netlify: 'basicsitebasic.netlify.app',
                    github:'https://github.com/nozipho97/basicsite.git'
                }
            ],
        }
    }
}
</script>
<style scoped>
.container{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    background-color: sandybrown;
}

.container h1{
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: bold;
    text-align: center;
    text-decoration: underline;
    
}


.card{
    margin-top: 70px;
    display: flex;

}

.card-body{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: saddlebrown;
}

.card-title{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: saddlebrown;
    font-weight: bold;
}
</style>