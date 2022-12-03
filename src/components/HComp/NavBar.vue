<template>

    <div class="container">


        <div>

            <img src="../../assets/img/avada-movers-logo.png" alt="">

        </div>


        <div>

            <ul>
                <li class="green">Home</li>
                <li>Rates</li>
                <li>Testimonials</li>
                <li>FAQ</li>
                <li>Blog</li>
                <li>Contact</li>
                <button> <b>FREE QUOTE</b> </button>
            </ul>

            

        </div>






    </div>


</template>



<script>

export default {
    name: 'NavBar'
}


</script>



<style lang="scss" scoped>
.container {
    width: 70%;
    margin: auto;
    margin-top: 1%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul{
    list-style-type: none;
    display: flex;
    align-items: center;

    li{
        font-weight: bolder;
        margin-right: 50px;
    }

    button{
        background-color: rgb(22, 117, 191);
        color: white;
        margin-right: 20px;
        padding: 12px 22px;
        border: 0px;
        border-radius: 22px;
    }
}

.green{
    color: rgb(106, 191, 22);
}

</style>