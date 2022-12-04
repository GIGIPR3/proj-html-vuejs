<template>

  <div>

    <GreenBar />

    <JumboComp />

    <BlueBar/>



  </div>

</template>


<script>

import GreenBar from '../components/HComp/GreenBar.vue'
/* import JumboTron from '../components/HComp/JumboTron.vue' */
import JumboComp from '../components/HComp/JumboComp.vue'
import BlueBar from '../components/HComp/BlueBar.vue'


export default {
  name: 'HeaderComp',
  components: {
    GreenBar,
    JumboComp,
    BlueBar
  }
}


</script>


<style lang="scss" scoped>

</style>