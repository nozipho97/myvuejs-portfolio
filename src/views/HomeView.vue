<template>
  <section class="home" id="Home">
    <div class="content">
<HomeVue/>
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
<style scoped>

</style>
