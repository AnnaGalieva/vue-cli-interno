<template>
  <Head />
  <router-view />
  <Footer />
</template>
  
<script>

import Head from './components/Head.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Head,
    Footer,
  }, data() {
    return {

    };
  },
}
</script>
  
 