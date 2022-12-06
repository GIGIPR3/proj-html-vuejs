<template>
    
    <div>

        <FirstComp/>

        <CardComp/>

        <JumboSecond/>

    </div>


</template>


<script>

import FirstComp from '../components/MComp/FirstComp.vue'
import CardComp from '../components/MComp/CardComp.vue'
import JumboSecond from '../components/MComp/JumboSecond.vue'

export default {
    name: 'MainComp',
    components: {
        FirstComp,
        CardComp,
        JumboSecond
    }
    
}

</script>

<style lang="scss" scoped>




</style>