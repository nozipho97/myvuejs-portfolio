<template>
<div>
  <nav class="navbar bg-body-tertiary">
    <div class="container-fluid">
        <h2>MN</h2>
    </div>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/testimonials">Testimonials</router-link>
    <router-link to="/projects">Projects</router-link>
    <router-link to="/contact">Contact</router-link>
    <router-link to="/Resume">Resume</router-link>
  </nav>
  

</div>
</template>

<script>
export default {
   name:'Header'
}
</script>

<style scoped>

</style>