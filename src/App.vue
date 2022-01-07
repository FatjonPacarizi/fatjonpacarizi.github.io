<template>
  <div>
    <NavBar/>
    <div id="app">
      <Home/>
      <AboutUs/>
      <Service/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Home from './components/Home.vue'
import AboutUs from './components/AboutUs.vue'
import Service from './components/Service.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Home,
    AboutUs,
    Service,
    Footer
  }
}
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #F6F6F6;
  font-family: system-ui;;
}
</style>
