<template>
  <div id="app">
  <Nav/>
  <div class="content">
    <Welcome/>
    <BasicInfo/>
    <Cards/>
    <!-- <Contact/> -->
    <Footer/>
  </div>
    
 
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'
import Welcome from './components/Welcome.vue'
import BasicInfo from './components/BasicInfo.vue'
import Cards from './components/Cards.vue'
// import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
  Nav, 
  Welcome, 
  BasicInfo, 
  Cards,
  // Contact,
  Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body{
  margin:0;
}

@font-face {
  font-family: 'Raleway';
  src: url('./assets/fonts/Raleway-Regular.ttf');
}
@font-face {
  font-family: 'Gobold';
  src: url('./assets/fonts/Gobold-Light.ttf');
}

.content{
  margin-top:3.3rem;
}
  
</style>
