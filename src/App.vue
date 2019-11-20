<template>
  <v-app id="App">
    <Navbar />
    <!-- <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-app-bar>-->

    <!-- <v-content>
      <HelloWorld />
    </v-content>-->
    <router-view />
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
// import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    Navbar
    // HelloWorld
  },
  data: () => ({
    //
  })
};
</script>
<style scoped>
/* @import "./assets/debug.css"; */
</style>
