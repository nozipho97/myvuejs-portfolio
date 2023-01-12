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




<style>
#app {
  font-family:Georgia, 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: saddlebrown;
  background-size: cover;
  justify-items: center;
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
