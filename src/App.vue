<template>
  <div id="app">
 <!--  <Portfolio />
    <Footer />
    <Header /> --> 
    <Exercice />
  </div>
</template>

<script>
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
import Header from "./components/header.vue";
import Exercice from "./components/exercice.vue";




export default {
  components: {
    Portfolio,
    Header,
    Footer,
    Exercice,


  },
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
</style>