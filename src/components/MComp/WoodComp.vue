<template>
    
    <div class="container">

        <div class="titleV">
            Request A Free Quote
        </div>

        <div class="text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        </div>

        <div>
            <button>CLICK HERE</button>
        </div>
    </div>  

</template>

<script>


</script>

<style lang="scss" scoped>

.container{
    height: 55vh;
    background-image: url(../../assets/img/avada-movers-request-quote-background.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    border-bottom: 15px solid rgb(106, 191, 22);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

button{
    background-color: rgb(22, 117, 191);
    color: white;
    font-weight: bold;
    border: 0px;
    padding: 15px 30px;
    border-radius: 25px;
    margin-top: 15%;
}

.titleV{
    color: rgb(106, 191, 22);
    font-size: 45px;
    font-weight: bolder;
/*     width: 20%; */
    margin-top: 1%;
    
}

.text{
    width: 40%;
    line-height: 30px;
    margin-top: 1%;
    font-weight: lighter;
    color: rgb(87, 86, 86);
}



</style>