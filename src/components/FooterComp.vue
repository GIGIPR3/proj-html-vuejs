<template>
    
    <div>

        <AboutComp/>

        <FooterGreenBar/>

    </div>




</template>

<script>

import AboutComp from '../components/FComp/AboutComp.vue'
import FooterGreenBar from '../components/FComp/FooterGreenBar.vue'


export default {
    name: 'FooterComp',
    components: {
        AboutComp,
        FooterGreenBar
    }

}

</script>


<style lang="scss" scoped>



</style>