<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    
    <!-- <PropTest msg="im a calc" v-bind:propB="food" :propC="state" :propD="phone"> </PropTest>  -->

    <Calculator > </Calculator>

  </div>
</template>

<script>

import PropTest from './components/PropTest.vue'
import Calculator from './components/Calculator.vue' 
export default {
  data(){
    return{
         name: 'app',
          food : 'egusi',
          state: 'enugu',
          phone: '09000990',
    }

  },


  components: {
    // HelloWorld
    PropTest,Calculator

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
