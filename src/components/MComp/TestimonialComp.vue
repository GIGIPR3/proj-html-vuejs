<template>

    <div class="sfondo">

        <div class="container">
            <div class="titoli">
                <div class="textG">
                    HAPPY CUSTOMERS
                </div>
                <div class="titleV">
                    Testimonials
                </div>
            </div>

            <div>
                <TreeClient class="card"/>
            </div>

            <div>
                <button>READ MORE TESTIMONIALS</button>
            </div>
            

        </div>




    </div>


</template>


<script>

import TreeClient from '../../components/MComp/TreeClient.vue'



export default {
    name: 'TestimonialComp',
    components: {
        TreeClient
    }
}


</script>


<style lang="scss" scoped>
.sfondo {
    background-image: url(../../assets/img/avada-movers-testimonial-background.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
}


.container {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.titoli{
    margin-bottom: 4%;
}

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

.card {
    width: 70%;
    display: flex;
    flex-direction: row;
    margin: auto;
}


button{
    background-color: rgb(22, 117, 191);
    color: white;
    font-weight: bold;
    border: 0px;
    padding: 15px 30px;
    border-radius: 25px;
    margin-top: 40%;
}
</style>