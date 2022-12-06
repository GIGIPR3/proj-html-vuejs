<template>
    
    <div>

        <FirstComp/>

        <CardComp/>

        <JumboSecond/>

        <TestimonialComp/>


    </div>


</template>


<script>

import FirstComp from '../components/MComp/FirstComp.vue'
import CardComp from '../components/MComp/CardComp.vue'
import JumboSecond from '../components/MComp/JumboSecond.vue'
import TestimonialComp from '../components/MComp/TestimonialComp.vue'

export default {
    name: 'MainComp',
    components: {
        FirstComp,
        CardComp,
        JumboSecond,
        TestimonialComp
    }
    
}

</script>

<style lang="scss" scoped>




</style>