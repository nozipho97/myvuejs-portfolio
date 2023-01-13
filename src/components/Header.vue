<template>
<div>
<header>
  <nav class="navbar bg-body-tertiary">
    <div class="container-fluid">
    </div>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/testimonials">Testimonials</router-link>
    <router-link to="/projects">Projects</router-link>
    <router-link to="/contact">Contact</router-link>
    <router-link to="/Resume">Resume</router-link>
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