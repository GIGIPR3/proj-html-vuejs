<template>

    <div class="jumbo">

        <NavBar />
        <div class="textC">
            <div class="titleG">
                <b>MOVING WITHOUT THE HASSLE</b>
            </div>

            <div class="titolo">
                <b>WE MAKE IT SIMPLE </b>
            </div>

            <div class="titleG">
                <b>PROFESSIONAL SERVICE WITH QUALITY AND CUSTOMER SATISFACTION</b>
            </div>
        </div>


    </div>


</template>


<script>

import NavBar from '../../components/HComp/NavBar.vue'

export default {
    name: 'SassoSass',
    components: {
        NavBar
    }
}



</script>


<style lang="scss" scoped>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.jumbo {
    height: 670px;
    background-image: url(../../assets/img/avada-movers-homeherobackground-final.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    padding-top: 1%;
}

.titleG {
    color: rgb(88, 88, 88);
    margin-top: 0.5%;
}

.titolo {
    font-size: 60px;
    margin-top: 0.5%;
}

.textC{
    text-align: center;
    margin-top: 9%;
}


</style>