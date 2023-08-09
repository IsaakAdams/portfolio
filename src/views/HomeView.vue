<template>
  <div>
    <Navbar />
    <Hello />
    <Skills />
    <Gallery />
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Skills from '../components/Skills.vue'
import Hello from '../components/Hello.vue'
import Gallery from '../components/Gallery.vue'
  export default {
    components : {
      Navbar,
      Skills,
      Hello,
      Gallery
    }
  }
</script>

<style lang="scss" scoped>

</style>
