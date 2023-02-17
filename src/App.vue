<template>
<div id="app">
  <Header/>
  <Main/>
  <Footer/>
</div>
</template>

<script>
import Header from "./components/ui/Header.vue"
import Footer from "./components/ui/Footer.vue"
import Main from "./components/main/Main.vue"
export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
#app, body {
  background: #5B0017;
}
</style>
