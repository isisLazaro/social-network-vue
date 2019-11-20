<template>
  <v-content>
    <v-container>
      <v-row no-gutters>
        <v-col>
          <div class="bckgrnd-img">
            <div class="bckgrnd-txt">
              <div class="text-center">
                <h1>
                  El espacio incluyente donde toda la comunidad de bodas se
                  conecta.
                </h1>
                <!-- <h2>
                Planear una boda puede ser muy complicado, quieres que sea
                perfecta, lo que siempre has soñado, pero a la vez que se ajuste
                a la realidad.
                </h2>-->
                <v-btn color="teal darken-4" dark>Inicia sesión</v-btn>
              </div>
            </div>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </v-content>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    // HelloWorld
  }
};
</script>
<style scoped>
* {
  color: #26a69a;
}

.container {
  padding: 0;
}

.bckgrnd-img {
  background: url("../assets/wedding-gay.jpg") bottom center;
  height: 90vh;
}
.bckgrnd-txt {
  background: #b2dfdb;
}
h1 {
  font-family: "Anton", sans-serif;
}

h2 {
  font-family: "Lobster", cursive;
}
</style>
