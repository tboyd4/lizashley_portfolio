<template>
  <div id="demo">
    <v-row justify="center" align="center">
      <v-col justify="center" align="center" cols="12" md="6">
        <v-row>
          <v-btn
            color="main main--text"
            @click="narrPlay"
            depressed
            outlined
            class="mx-1 my-3"
          >
            Click for Narrative Demo
          </v-btn>
          <v-btn
            color="main main--text"
            @click="commPlay"
            depressed
            outlined
            class="mx-1 my-3"
          >
            Click for Commercial Demo
          </v-btn>
        </v-row>
      </v-col>
      <v-col cols="12" md="6">
        <v-img max-height="705" src="/pic3.JPG"></v-img>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import {Howl, Howler} from 'howler';
const narrSound = new Howl({
  src: ['/narrdemo.mp3'],
})
const commSound = new Howl({
  src: ['/commdemo.mp3'],
})
export default {
  methods: {
    narrPlay() {
      narrSound.play()
    },
    commPlay() {
      commSound.play()
    },
  },
}
</script>

<style scoped></style>
