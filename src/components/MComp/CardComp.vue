<template>

    <div class="container">
        
        <div class="textG">
            WE ARE A PROFESSIONAL
        </div>
        <div class="titleV">
            Full-Service Solution
        </div>

        <div>
            <ThreeCard class="altezza" />
        </div>


    </div>







</template>


<script>

import ThreeCard from '../../components/MComp/ThreeCard.vue'

export default {
    name: 'CardComp',
    components: {
        ThreeCard
    }
}

</script>


<style lang="scss" scoped>
.container {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    /*     padding-top: 2%; */
}

/* .container1{
    display: flex;
} */

.textG {
    color: rgb(75, 74, 74);
    font-weight: bold;
    /*     margin-top: 1%; */

}

.titleV {
    color: rgb(106, 191, 22);
    font-size: 45px;
    font-weight: bolder;
    /*     width: 20%; */
    margin-top: 1%;
    margin-bottom: 3%;
}

.altezza {
    height: 550px;
    width: 100%;
    margin-bottom: 2%;
    display: flex;
    flex-direction: row;
}
</style>