<template>
    <div>
        <h1>Testimonials</h1>
        <div class="container">
            <div class="card" style="width: 18rem; height:30rem; margin:60px;" v-for="person in people">
                <img :src="person.image" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">{{person.name}}</h5>
                  <p class="card-text">{{person.msg}}</p>
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
                    name: 'Nontobeko Mhlongo',
                    status: 'LC Student',
                    msg: 'Nozipho is smart and very approachable, humble and  well spoken.',
                    image:'https://i.postimg.cc/FsGBGZvv/C11-Nontobeko-Mhlongo-1.jpg'
                },
                {
                    name: 'Keren Bruce',
                    status: 'LC Student',
                    msg: 'Nozipho is a wonderful hard-working worker with a soft kind personality and a warm heart. She always ensures that goals are being met the way they are required to. She is highly creative and creates beautiful innovative projects which showcase her amazing technical abilities. She would make a highly efficient and wonderful asset to your company.',
                    image:'https://i.postimg.cc/7YqRgRpX/keren-bruce.jpg'
                },
                {
                    name: 'Asandile Langeni',
                    status: 'LC Student',
                    msg: 'Nozipho is a girl that is down to earth and she is always in her element. She is a hard worker and a team player. She loves to be surrounded by friends and family.  She is always willing to go an extra mile in order to pull her weight.',
                    image:'https://i.postimg.cc/3N2M3jVq/asa.jpg'
                },
                {
                    name: 'Sivuyisiwe Cele',
                    status: 'LC Student',
                    msg: 'Nozipho is one dedicated young lady and I have worked with her couple of times and she is one organized, puntual and detailed person.',
                    image:'https://i.postimg.cc/50Vbt3fm/C11-Sivuyisiwe-1.jpg'
                },
                {
                    name:'Ryan Thomas',
                    status: 'LC Lecture',
                    msg: 'Nozipho very rarely struggles to the point of needing any help, which shows   off traits that presents her as a really fast & strong learner that is able to assess a problem at hand and solve it within minutes. Nozipho also comes across as shy and quiet, but once engaging in conversation she shows off her great sense of humor.',
                    image:'https://i.postimg.cc/26fVzGKp/ryan.jpg'
                },
                {
                    name: 'Abdul-Azeez Kemp',
                    status: 'LC Student',
                    msg: 'Nozipho is very ambitious and very aunthentic. Puts attention to detail and very observant.',
                    image:'https://i.postimg.cc/1t9rPkVc/C11-Abdul-Azeez-Kemp-1.jpg'
                }
            ],
        }
    }
}
</script>
<style>
    .container{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        background-color: sandybrown;
    }

    .card{
        height: 10rem;
    }

    .card-body{
        font-family: Georgia, 'Times New Roman', Times, serif;
        color: saddlebrown;
        text-size-adjust: 2rem;
        font-size: small;
    }

    .card :hover{
        box-shadow: 10px 10px 0  sandybrown , -10px -10px 0  saddlebrown;
    }

    .card-title{
        font-family: Georgia, 'Times New Roman', Times, serif;
        color: saddlebrown;
        font-weight: bold;
        text-decoration: underline;
    }
</style>