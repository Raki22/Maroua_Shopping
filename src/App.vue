<template>
    
    <Header />
   <Portfolio />
   <Join />
   <News />
</template>

<script>
import Header from './components/Header.vue'
import Portfolio from './components/Portfolio.vue';
import Join from './components/Join.vue';
import News from './components/News.vue';

export default {
  name: 'App',
  components: {
    Header,
    Portfolio,
    Join,
    News
},

}
</script>

<style>

</style>