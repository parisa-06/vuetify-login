<template>
 
 <HelloWorld/>
  
</template>

<style>

    @import './assets/css/fonts.css';
   
</style>


<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
