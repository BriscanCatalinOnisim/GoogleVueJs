<template>
  <v-app>
    <div id="app">
      <Navbar/> 
      <Spacer/>
      <Content/>
      <Spacer/>
      <FooterRo/>
      <Footer/>
    </div>
  </v-app>
</template>

<script>
import Navbar from './components/navbar.vue';
import Footer from './components/footer.vue';
import FooterRo from './components/footerRo.vue';
import Content from './components/content.vue';
import Spacer from './components/spaces.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    FooterRo,
    Content,
    Spacer,
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

router-link:hover {
  text-decoration: underline;
}


a1 {
  margin: 10px 10px;
  align-self: center;
}

a1:hover {
  text-decoration: underline;
}

a {
  margin: 10px 10px;
  align-self: center;
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

.textLink {
  text-decoration: none;
  padding-left: 20px;
  color: black;
  color: rgba(0, 0, 0, 0.54);
}

.textLink1 {
  text-decoration: none;
  color: black;
  color: rgba(0, 0, 0, 0.54);
}
</style>
