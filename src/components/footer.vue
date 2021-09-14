<template>
  <div class="__footer">
    <v-row class="text-left">
      <v-col>
        <div class="pa-2" outlined tile>Romania</div>
      </v-col>
    </v-row>
    <v-row class="__footer-links" no-gutters>
      <v-col>
        <div class="links" outlined tile>
          <router-link to="/">Advertising</router-link>
          <router-link to="/">Business</router-link>
          <router-link to="/">About</router-link>
          <router-link to="/">How Search works</router-link>
        </div>
      </v-col>
      <v-col>
        <div class="links __links_right" outlined tile>
          <router-link to="/">Privacy</router-link>
          <router-link to="/">Terms</router-link>
          <router-link to="/">Settings</router-link>
        </div>
      </v-col>
    </v-row>
  </div>
</template>
<style scoped>
.__footer {
  color: #5f6368;
  font-size: 14.5px;
  background: #f2f2f2;
  border-top: 1px solid #d2d2d2;
  position: absolute;
  bottom: 0;
  width: 100%;
}
.__links_right {
  padding-left: 10px;
}
.links {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 0 25px;
  background-color: #f2f2f2;
  color: rgba(0, 0, 0, 0.54);
}
.links a {
  padding-right: 20px;
}
.__footer-links {
  justify-content: space-between;
  border-top: 1px solid #d2d2d2;
}
a:visited {
  color: #5f6368;
}
a {
  color: #5f6368;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
</style>