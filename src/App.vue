<template>
  <Head />
  <HomePage />
  <Project />
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
import Project from './components/Project.vue';

export default {
  name: 'App',
  components: {
    Head,
    HomePage,
    Blog,
    BlogDetails,
    Footer,
    Project
}, data() {
    return {

    };
  },
}
</script>
  
 