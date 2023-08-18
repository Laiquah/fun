<template>
  <Navbar/>
    <router-view/>
  <Footer/>
</template>

<script>
import Navbar from './components/NavbarComp.vue'
import Footer from './components/FooterComp.vue'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@10..48,800&display=swap');

#app {
  font-family: 'Bricolage Grotesque', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}

nav {
  padding: 30px;
  color: black;
}

a{
  text-decoration: none !important;
  color: black !important;
}
</style>
