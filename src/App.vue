<template>
    
    <Header />
   <Portfolio />
   <Join />
   <News />
   <Testimonial />
</template>

<script>
import Header from './components/Header.vue'
import Portfolio from './components/Portfolio.vue';
import Join from './components/Join.vue';
import News from './components/News.vue';
import Testimonial from './components/Testimonial.vue';

export default {
  name: 'App',
  components: {
    Header,
    Portfolio,
    Join,
    News,
    Testimonial
},

}
</script>

<style>

</style>