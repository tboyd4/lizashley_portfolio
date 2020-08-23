<template>
    <div>
        <v-app-bar
      color="white"
      class="font-header"
      fixed
      hide-on-scroll
      flat
    >

      <v-spacer></v-spacer>

      <v-btn color="main main--text" @click="$vuetify.goTo('#home')" depressed outlined class="mx-1">
        Home
      </v-btn>

      <v-btn color="main main--text" @click="$vuetify.goTo('#resume')" depressed outlined class="mx-1">
        Resume
      </v-btn>

      <v-btn color="main main--text" @click="$vuetify.goTo('#demo')" depressed outlined class="mx-1">
        Demo
      </v-btn>

      <v-btn color="main main--text" @click="$vuetify.goTo('#contact')" depressed outlined class="mx-1">
        Contact Me
      </v-btn>
    </v-app-bar>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.font-header {
    font-family: 'Syncopate', sans-serif;
}

</style>