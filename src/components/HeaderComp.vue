<template>
    
    <div>

        <GreenBar/>

<!--         <NavBar/> -->
<!--         <JumboTron/> -->
        <JumboComp/>
    </div>

</template>


<script>

import GreenBar from '../components/HComp/GreenBar.vue'
/* import JumboTron from '../components/HComp/JumboTron.vue' */
import JumboComp from '../components/HComp/JumboComp.vue'



export default {
  name: 'HeaderComp',
  components: {
    GreenBar,
/*     NavBar, */
/*     JumboTron */
    JumboComp
  }
}


</script>


<style lang="scss" scoped>



</style>