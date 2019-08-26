<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Layer</span>
        <span class="font-weight-light"> Área Médica</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-content>
      <FichaMedica />
    </v-content>
  </v-app>
</template>

<script>
import FichaMedica from './components/FichaMedica';

export default {
  name: 'App',
  components: {
    FichaMedica,
  },
  data: () => ({
    //
  }),
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
