<template>
    <div>
        <h1>Testimonials</h1>
        <div class="card" style="width: 18rem;" v-for="person in people">
            <img :src="person.image" class="card-img-top" >
            <div class="card-body">
              <h5 class="card-title">{{person.name}}</h5>
              <p class="card-text">{{person.msg}}</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
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
                    msg: 'Nozipho is a girl that is down to earth and she is always in her element. She is a hard worker and a team player. She loves to be surrounded by friends and family.  She is always willing to go an extra mile in order to pull her weight.<',
                    image:'https://i.postimg.cc/ZY8gvmDC/asandile-langeni.jpg'
                },
                {
                    name: 'Sivuyisiwe Cele',
                    status: 'LC Student',
                    msg: 'Nozipho is one dedicated young lady and I have worked with her couple of times and she is one organized, puntual and detailed person.',
                    image:'https://i.postimg.cc/K8Hsh84s/C11-Sivuyisiwe-3.jpg'
                },
                {
                    name: 'Oslin Johnson',
                    status: 'LC Student',
                    msg: 'Nozipho very rarely struggles to the point of needing any help, which shows   off traits that presents her as a really fast & strong learner that is able to assess a problem at hand and solve it within minutes. Nozipho also comes across as shy and quiet, but once engaging in conversation she shows off her great sense of humor.',
                    image:'https://i.postimg.cc/J0Rg09WK/oslin.jpg'
                }
            ],
        }
    }
}
</script>
<style>
    
</style>