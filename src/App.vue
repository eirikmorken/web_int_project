<template>
  <v-app>
    
    
    <v-content>
      <Footer />
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import Footer from './components/layout/Footer';

export default {
  name: 'App',
  components: {
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
