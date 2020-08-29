<template>
  <v-form class="form" id="contact" ref="form" v-model="valid" lazy-validation>

    <h1 class="contact-head pb-10">Let's Connect!</h1>
    <v-text-field
      v-model="name"
      :counter="15"
      :rules="nameRules"
      label="Name"
      outlined
      color="main"
      required
    ></v-text-field>

    <v-text-field
      v-model="email"
      :rules="emailRules"
      label="E-mail"
      color="main"
      outlined
      required
    ></v-text-field>

    <v-text-field
      v-model="message"
      :rules="[(v) => !!v || 'Message is required']"
      label="Message"
      color="main"
      outlined
      required
    ></v-text-field>

    <v-btn :disabled="!valid" color="main white--text" class="mr-4" @click="submit">
      Submit
    </v-btn>
  </v-form>
</template>

<script>
export default {
  data: () => ({
    valid: true,
    name: '',
    nameRules: [
      (v) => !!v || 'Name is required',
      (v) => (v && v.length <= 15) || 'Name must be less than 15 characters',
    ],
    email: '',
    emailRules: [
      (v) => !!v || 'E-mail is required',
      (v) => /.+@.+\..+/.test(v) || 'E-mail must be valid',
    ],
    select: null,
    message: '',
  }),

  methods: {
    submit() {
      console.log("hello")
    }
  },
}
</script>

<style scoped>
.contact-head {
  font-family: 'Actor', sans-serif;
  color: #e1655e;
  font-weight: thin;
  font-size: 30px;
}

.form {
    border: #e1655e solid 1px;
    padding: 15px;
    border-radius: 20px;
}
</style>
