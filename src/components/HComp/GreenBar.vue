<template>
    
    <div class="nav">
        <div class="container">

            <div class="testo">
                <i class="fa-solid fa-phone-flip"></i>
                Call us for a Free Quote: 1.800.555.6789
            </div>

            <div class="loghi">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
            </div>



        </div>
    </div>


</template>


<script>
    export default{
        name: 'GreenBar'
    }


</script>



<style lang="scss" scoped>

/* sfondo VERDE rgb(106, 191, 22) */

.nav{
    height: 44px;
    background-color: rgb(106, 191, 22);
    color: white;
}

.container{
    height: 100%;
    width: 70%;
/*     background-color: aquamarine; */
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.testo{
    font-size: small;
}

i{
    margin-right: 20px;
}


</style>