<template>
    <div class="Heading">Resume</div>
    <div class="content">
        <div class="card mb-4" style="max-width: 540px; margin-left:30%;" v-for="info in resume">
            <div class="row g-0">
              <div class="col-md-5">
                <img :src="info.image" class="img-fluid rounded start" style="display:flex; margin-left:65%;" alt="">
              </div>
              <div class="col-md-8" style="box-shadow:burlywood;">
                <div class="card-body" style="justify-content:center; color:saddlebrown; font-weight:bold;">
                  <h5 class="card-title">{{info.name}}</h5>
                  <p class="card-text">{{info.content}}</p>
                  <p class="card-text">{{info.email}}</p>
                  <p class="card-text">{{info.address}}</p>
                  <p class="card-text">{{info.contact}}</p>
                  <p class="card-text">{{info.experience}}</p>
                  <p class="card-text">{{info.skills}}</p>
                  <p class="card-text">{{info.education}}</p>
                  <p class="card-text">{{info.projects}}</p>
                <p class="card-text"><small class="text-muted">Last updated 1 min ago</small></p>
                </div>
              </div>
            </div>
          </div>
        
        
    </div>
</template>
<script>
export default {
    data() {
        return {
            resume: [
                {
                    name: 'Nozipho Mayila',
                    address: '31989 Lwesine Streeet Makhaza Khayelitsha',
                    email: 'mayilanozipho@gmail.com',
                    contact: '0683264041',
                    content: 'Attentive, compassionate and results-oriented individual. Excellent communication skills both spoken and written.',
                    image:'https://i.postimg.cc/SRRk1Pw0/Nozipho-Mayila-picture-1.jpg'
                }, 
                {
                    experience: 'ND Marketing 2019-2020, ZA Online Cafe 2020-2021',
                },
                {
                     skills:'Administrative,Adaptability,Emotional intelligence,Attention to detail,Technology,Working well under pressure'
                },
                {
                    education:'IT Technical Support NQFL4, CTU training solutions, Chris Hani Secondary School'
                },
                {
                    projects:'Portfolio, Calculator, E-Commerce websites'
                }
            ]
        }
    }
}
</script>

<style scoped>


</style>