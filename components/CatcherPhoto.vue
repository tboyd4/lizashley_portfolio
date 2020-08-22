<template>
  <div id="home">
    <v-row justify="center" align="center">
      <v-col justify="center" align="center" cols="12" md="6">
        <v-row>
          <v-responsive class="icon-head">LA</v-responsive>
        </v-row>
        <v-row>
          <v-responsive class="icon-sub">LIZ ASHLEY</v-responsive>
        </v-row>
        <v-row>
          <v-responsive class="icon-title">voice over artist</v-responsive>
        </v-row>
      </v-col>
      <v-col cols="12" md="6">
        <v-img max-height="705" src="/pic1.JPG"></v-img>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.icon-head {
  font-family: 'Actor', sans-serif;
  color: white;
  text-shadow: -2px 0 #e1655e, 0 2px #e1655e, 2px 0 #e1655e, 0 -2px #e1655e;
  font-weight: bold;
  font-size: 120px;
}
.icon-sub {
  font-family: 'Actor', sans-serif;
  color: #e1655e;
  font-weight: thin;
  font-size: 45px;
}
.icon-title {
  font-family: 'Actor', sans-serif;
  color: #e1655e;
  font-weight: thin;
  font-size: 30px;
}
</style>
