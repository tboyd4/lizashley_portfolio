<template>
    <div>
        <v-app-bar
      color="white"
      class="font-header"
      flat
    >

      <v-spacer></v-spacer>

      <v-btn color="main main--text" depressed outlined class="mx-1">
        Home
      </v-btn>

      <v-btn color="main main--text" depressed outlined class="mx-1">
        Resume
      </v-btn>

      <v-btn color="main main--text" depressed outlined class="mx-1">
        Demo
      </v-btn>

      <v-btn color="main main--text" depressed outlined class="mx-1">
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