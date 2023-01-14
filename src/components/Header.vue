<template>
<div>
<header>
  <nav class="navbar bg-body-tertiary">
    <div class="container-fluid">
    </div>
    <router-link to="/"><i class="fa-solid fa-house-user"></i>Home</router-link>
    <router-link to="/about"><i class="fa-solid fa-address-card"></i>About</router-link>
    <router-link to="/testimonials"><i class="fa-solid fa-comment"></i>Testimonials</router-link>
    <router-link to="/projects"><i class="fa-solid fa-rectangle-vertical-history"></i>Projects</router-link>
    <router-link to="/contact"><i class="fa-solid fa-address-book"></i>Contact</router-link>
    <router-link to="/Resume"><i class="fa-solid fa-file"></i>Resume</router-link>
  </nav>
</header>
</div>
</template>

<script>
export default {
   name:'Header'
}
</script>

<style scoped>
header{
  font-family:Georgia, 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: sandybrown;
  background-color: sandybrown;
  justify-items: center;
  height: 2px;
}

nav {
  color:sandybrown;
  padding: 20px;
}

nav a {
  font-weight: bold;
  color: sandybrown;
  text-decoration: none;
  justify-content: space-evenly;
  margin-left:50px;
  margin-right:50px;

}

</style>