<template>
  <div>
    <mitau-navigation> </mitau-navigation>
    
     <!-- project carousel -->
        <project-carousel></project-carousel>
      <!-- introduction content -->
        <br />
        <h1>Welcome to the portfolio</h1>
     <!-- project list with completion status -->
        <project></project>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap-vue/dist/bootstrap-vue.css';
import Project from '~/components/Project.vue';
import MitauNavigation from '~/components/Navigation.vue';
import ProjectCarousel from '~/components/ProjectCarousel.vue';

export default {
   components:{
    Project,
    Navigation,
    ProjectCarousel
   }
  }

</script>

<style>

</style>
