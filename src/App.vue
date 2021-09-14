<template>
  <v-app>
    <div id="app">
      <div class="nav"><Navbar/> </div>
      
      <router-view />
      <div><FooterRo/></div>
      <div><Footer/></div>
    </div>
  </v-app>
</template>

<script>
import Navbar from './components/navbar.vue';
import Footer from './components/footer.vue';
import FooterRo from './components/footerRo.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    FooterRo,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.nav {
  margin-top: 10px;
}

html {
  min-width: 400px;
}

a:visited {
  color: rgba(0, 0, 0, 0.87);
}

a {
  color: rgba(118, 122, 122, 0.87);
}

a:hover {
  text-decoration: underline;
}
</style>
