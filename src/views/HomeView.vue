<template>
  <section class="home" id="Home">
    <div class="content">
        <h1>Hello There!</h1>
        <p>My Name is Nozipho Mayila</p>
    </div>
  </section>
</template>

<script>
import HomeVue from '@/components/HomeVue.vue';
export default {
  name: 'HomeView',
  components: {
    HomeVue
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

section{
  background-color: saddlebrown;
  }

</style>
