<template>
    
    <Header />
   <Portfolio />
   <Join />
   <News />
   <Testimonial />
   <WaitingFor />
   <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Portfolio from './components/Portfolio.vue';
import Join from './components/Join.vue';
import News from './components/News.vue';
import Testimonial from './components/Testimonial.vue';
import WaitingFor from './components/WaitingFor.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Portfolio,
    Join,
    News,
    Testimonial,
    WaitingFor,
    Footer,
},

}
</script>

<style>

</style>