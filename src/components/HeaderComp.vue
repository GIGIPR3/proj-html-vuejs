<template>
    
    <div>

        <GreenBar/>

<!--         <NavBar/> -->
        <!-- <JumboTron/> -->
        <SassoSass/>
    </div>

</template>


<script>

import GreenBar from '../components/HComp/GreenBar.vue'
/* import JumboTron from '../components/HComp/JumboTron.vue' */
import SassoSass from '../components/HComp/SassoSass.vue'



export default {
  name: 'HeaderComp',
  components: {
    GreenBar,
/*     NavBar, */
    /* JumboTron, */
    SassoSass
  }
}


</script>


<style lang="scss" scoped>



</style>