<template>
    
    <div>

        <FirstComp/>

        <CardComp/>



    </div>


</template>


<script>

import FirstComp from '../components/MComp/FirstComp.vue'
import CardComp from '../components/MComp/CardComp.vue'

export default {
    name: 'MainComp',
    components: {
        FirstComp,
        CardComp
    }
    
}

</script>

<style lang="scss" scoped>




</style>