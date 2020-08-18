<template>
  <v-app>
    <head-bar></head-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
import HeadBar from '../components/HeadBar.vue'
export default {
  components: {
    HeadBar
  }
}
</script>
