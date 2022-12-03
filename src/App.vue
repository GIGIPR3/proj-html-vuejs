<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

      <HeaderComp/>
      <MainComp/>
      <FooterComp/>



  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FooterComp from './components/FooterComp.vue'



export default {
  name: 'App',
  components: {
    /* HelloWorld */
    HeaderComp,
    MainComp,
    FooterComp
  }
}
</script>

<style lang="scss">
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap');
  font-family: 'Noto Sans', sans-serif;
}

/* @import url('https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap'); */


</style>
