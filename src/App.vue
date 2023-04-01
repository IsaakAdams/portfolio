<!-- HTML -->
<template>
  <MainCard />
  <ProjectsCard />
</template>


<!-- JavaScript -->
<script setup>
import MainCard from './components/MainCard.vue'
import ProjectsCard from './components/ProjectsCard.vue'
</script>


<!-- Styling -->
<style>
  body {
    margin: 0;
    background-color: #d6edff;
  }

  #app {
    font-family: Avenif, Helvetica, Arial, sans-serif;
    text-align: center;
    
  }
</style>
