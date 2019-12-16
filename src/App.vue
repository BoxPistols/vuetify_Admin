
<template>
  <v-app>

    <v-navigation-drawer app v-model="drawer" clipped>Navigation Lists</v-navigation-drawer>

    <v-app-bar color="primary" dark app clipped-left>
      <v-app-bar-nav-icon  @click="drawer=!drawer"></v-app-bar-nav-icon>
      <v-toobar-title>Vuetify</v-toobar-title>
    </v-app-bar>

    <v-footer color="primary" dark app>
      Vuetify
    </v-footer>
  <!-- <v-content>
    <HelloWorld />
  </v-content> -->
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
export default {
  data(){
    return{
        drawer: null
    }
  }
}
</script>
