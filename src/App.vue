<template>
  <v-app>
    <v-main>
      <RegisterForm/>
    </v-main>
  </v-app>
</template>

<script>
import RegisterForm from './components/RegisterForm';

export default {
  name: 'App',

  components: {
    RegisterForm,
  },

  data: () => ({
    //
  }),
};
</script>
