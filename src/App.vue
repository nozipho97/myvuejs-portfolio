<template>
 <Header/>
 <router-view/>
 <Footer/>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer..vue';



export default {
  name: 'App',
  components:
    { Footer, Header}
}


</script>




<style scoped>
#app {
  font-family:Georgia, 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: saddlebrown;
  background-size: cover;
  justify-items: center;
}

</style>
