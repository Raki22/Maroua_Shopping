<template>
    
    <Header />
   <Portfolio />
   <Join />
</template>

<script>
import Header from './components/Header.vue'
import Portfolio from './components/Portfolio.vue';
import Join from './components/Join.vue';

export default {
  name: 'App',
  components: {
    Header,
    Portfolio,
    Join
},

}
</script>

<style>

</style>