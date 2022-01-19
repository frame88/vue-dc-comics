<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>

  <!-- Descrizione:
Create un nuovo progetto utilizzando Vue CLI e definite i componenti necessari per strutturare il layout come da screenshot allegato.
Concentratevi poi sulla parte grafica e SCSS creando a mano i menu. -->

</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";




export default {
  name: "App",
  components: {
    //HelloWorld,
    Header,
    Main,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss" 
</style>
