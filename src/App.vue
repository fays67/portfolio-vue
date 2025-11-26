<template>
  <div id="app">
    <Portfolio />
    <Footer />
    <Header />
  </div>
</template>

<script>
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
import Header from "./components/header.vue";




export default {
  components: {
    Portfolio,
    Header,
    Footer,
  },
};
</script>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
</style>