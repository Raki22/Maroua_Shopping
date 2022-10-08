<script>
  import Navbar from './Navbar.vue';
  import Slogan from './Slogan.vue'
  
  export default {
    name: 'Header',
    components: {
      Navbar,
      Slogan
    },
  
  }
  </script>

<template>
  <div class="section1">
    <Navbar />
    <Slogan title="Tagline brief simple wht company its all about"
            caption="Lorem ipsum dolor sit amet, consectetur adipiscing elit."
    />
  </div>
</template>

<style scoped>
.section1 {
  width: 100%;
  height: 620px;
  background-image: url('@/assets/images/header-bg.png');
  background-size: cover;
}

</style>
