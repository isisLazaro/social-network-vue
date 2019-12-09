<template>
  <v-content>
    <v-card width="500" class="mx-auto mt-5">
      <v-card-title>
        <h1 class="display-1">This is an about page</h1>
      </v-card-title>
      <v-card-text>
        <v-form>
          <v-text-field
            label="Nombre de usuario"
            prepend-icon="mdi-account-circle"
          />
          <v-text-field
            :type="showPassword ? 'text' : 'password'"
            label="Contraseña"
            prepend-icon="mdi-lock"
            :append-icon="showPassword ? 'mdi-eye' : 'mdi-eye-off'"
            @click:append="showPassword = !showPassword"
          />
        </v-form>
      </v-card-text>
      <v-divider></v-divider>
      <v-card-actions>
        <v-btn color="success">Regístrate</v-btn>
        <v-spacer></v-spacer>
        <v-btn color="info">Conéctate</v-btn>
      </v-card-actions>
    </v-card>
  </v-content>
</template>
<script>
// @ is an alias to /src
export default {
  name: "login",
  data: () => ({
    showPassword: false
  })
};
</script>
