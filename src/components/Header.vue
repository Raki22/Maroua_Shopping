<script>
  import Navbar from './Navbar.vue'
  
  export default {
    name: 'Header',
    components: {
      Navbar
    },
  
  }
  </script>

<template>
  <div class="section1">
    <Navbar />
  <div class="container">
    <h1>Tagline brief simple wht compani its all about</h1>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
    
    </div>
  </div>
</template>

<style scoped>
.section1 {
  width: 100%;
  height: 600px;
  background-image: url('@/assets/header-bg.png');
  background-size: cover;
}

</style>
