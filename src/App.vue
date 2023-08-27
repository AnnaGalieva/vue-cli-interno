<template>
  <Head />
  <HomePage />
  <Project />
  <ProjectDetails />
  <Swipers />
  <Blog />
  <BlogDetails />
  <NotFound />
  <Footer />
</template>
  
<script>

import Head from './components/Head.vue';
import HomePage from './components/HomePage.vue';
import Blog from './components/Blog.vue';
import Footer from './components/Footer.vue';
import BlogDetails from './components/BlogDetails.vue';
import Project from './components/Project.vue';
import ProjectDetails from './components/ProjectDetails.vue';
import Swipers from './components/Swipers.vue';
import NotFound from './components/NotFound.vue';

export default {
  name: 'App',
  components: {
    Head,
    HomePage,
    Blog,
    BlogDetails,
    Footer,
    Project,
    ProjectDetails,
    Swipers,
    NotFound
}, data() {
    return {

    };
  },
}
</script>
  
 