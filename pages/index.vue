<template>
  <v-layout>
    <v-container>
      <div class="my-16"></div>
      <catcher-photo></catcher-photo>
      <div class="my-16"></div>
      <div class="my-16"></div>
      <div class="py-16"></div>
      <resume></resume>
      <div class="my-16"></div>
      <div class="py-16"></div>
      <demo></demo>
      <div class="my-16"></div>
      <div class="py-16"></div>
    </v-container>
  </v-layout>
</template>

<script>
import CatcherPhoto from '../components/CatcherPhoto.vue'
import Resume from '../components/Resume.vue'
import Demo from '../components/Demo.vue'
export default {
  components: {
    CatcherPhoto,
    Resume,
    Demo,
  },
}
</script>
<style></style>
