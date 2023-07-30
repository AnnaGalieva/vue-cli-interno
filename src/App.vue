<template>
  <Head />
  <HomePage />
  <Blog />
  <BlogDetails />
  <Footer />
</template>
  
<script>

import Head from './components/Head.vue';
import HomePage from './components/HomePage.vue';
import Blog from './components/Blog.vue';
import Footer from './components/Footer.vue';
import BlogDetails from './components/BlogDetails.vue';

export default {
  name: 'App',
  components: {
    Head,
    HomePage,
    Blog,
    BlogDetails,
    Footer
  }, data() {
    return {

    };
  },
}
</script>
  
 