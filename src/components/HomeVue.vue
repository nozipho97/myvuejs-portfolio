<template>
  <div>
      <section class="home" id="Home">
        <div class="content1">
        </div>

        <div class="content2">
          <h1>Hello There!</h1>
          <div class="profile_content">
            <div class="circle"></div>
            <div class="profile"></div>
          </div>
          <div class="profile_content2">
            <h1 class="name">Nozipho Mayila</h1>
            <h2 class="occupation">Web Developer</h2>
          </div>
        </div>

      </section>

    
  </div>
  </template>
  
  <script>
  
  export default {
    name: 'HomeVue',
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Georgia, 'Times New Roman', Times, serif;
}
body {
  height: 100vh;
  width: 100%;
  background-color: sandybrown !important;
}
.content2{
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background-color: #ECECEC;
  gap: 2rem;
}

.content2 h1{
  color: saddlebrown;
  font-weight: bold;
  text-decoration:underline;
}
.profile_content{
  aspect-ratio: 1/1;
  width: min(400px,90%);
  position: relative;
}
.circle{
  position: absolute;
  width: 100%;
  height: 100%;
  box-shadow: 10px 10px 0 saddlebrown , -10px -10px 0  sandybrown;
  border-radius: 50%;
  animation: rotate 4s infinite linear;
}
.profile{
  border-radius: 50%;
  width: 100%;
  height: 100%; 
  background-image: url(https://i.postimg.cc/SRRk1Pw0/Nozipho-Mayila-picture-1.jpg);
  background-size: 100%;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  transition: all 0.2s ease-in-out;
  position: absolute;
}
.name{
  color:saddlebrown;

}
.occupation{
  color: sandybrown;
}
.profile:hover{
  background-size: 110%;
  box-shadow: 10px 10px 0  sandybrown , -10px -10px 0  saddlebrown;
}
.profile_content2{
  text-align: center;
}
@keyframes rotate {
  to{
    transform: rotate(360deg);
  }
}
</style>
  