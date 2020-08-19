<template>
  <v-layout>
    <v-container>
      <div class="my-12"></div>
      <catcher-photo></catcher-photo>
      <div class="my-12"></div>
      <div class="my-12"></div>
      <resume></resume>
    </v-container>
  </v-layout>
</template>

<script>
import CatcherPhoto from '../components/CatcherPhoto.vue'
import Resume from '../components/Resume.vue'
export default {
  components: {
    CatcherPhoto,
    Resume,
  },
}
</script>
<style></style>
