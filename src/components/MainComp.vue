<template>
    
    <div>

        <FirstComp/>

        <CardComp/>

        <JumboSecond/>

        <TestimonialComp/>

        <WoodComp/>

    </div>


</template>


<script>

import FirstComp from '../components/MComp/FirstComp.vue'
import CardComp from '../components/MComp/CardComp.vue'
import JumboSecond from '../components/MComp/JumboSecond.vue'
import TestimonialComp from '../components/MComp/TestimonialComp.vue'
import WoodComp from '../components/MComp/WoodComp.vue'

export default {
    name: 'MainComp',
    components: {
        FirstComp,
        CardComp,
        JumboSecond,
        TestimonialComp,
        WoodComp
    }
    
}

</script>

<style lang="scss" scoped>




</style>