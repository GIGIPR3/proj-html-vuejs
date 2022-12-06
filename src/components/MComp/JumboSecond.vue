<template>

    <div class="container">
        <div class="contenitore">

            <div class="card">
                <div class="textW">
                    WE REMOVE THE HEADACHE FROM MOVING
                </div>
                <div class="titoloW">
                    Move With Ease
                </div>
                <div class="linea"></div>
                <div class="text">
                    With our super simple service we can take you from getting a quote, right through to being in your
                    new home with all of your belongings securely packed and safely delivered, even in the rooms of your
                    choice.
                </div>
                <div>
                    <button>GET A FREE QUOTE</button>
                </div>
            </div>

        </div>



    </div>


</template>

<script>

export default {
    name: 'JumboSecond'
}



</script>

<style lang="scss" scoped>
.container {
    height: 83vh;
    background-image: url(../../assets/img/avada-movers-movewithease-background-new.jpg);
    background-size: cover;
    background-repeat: no-repeat;

}

.contenitore{
    
}

.card {
    background-color: rgb(106, 191, 22);
    height: 450px;
    width: 600px;
    border: 20px solid rgb(87, 155, 18);
    display: flex;
    flex-direction: column;
    text-align: center;
    line-height: 30px;
    justify-content: center;
    align-items: center;
    /*     justify-content: center; */
    padding: 1%;
}

.textW {
    font-weight: bold;
    color: white;
}

.titoloW {
    color: white;
    font-weight: bold;
    font-size: 45px;
    margin-top: 3%;
}

.linea {
    height: 1px;
    width: 65%;
    background-color: rgb(122, 219, 26);
    margin-top: 5%;
}


.text {
    color: white;
    margin-top: 3%;
}

button {
    background-color: rgb(22, 117, 191);
    color: white;
    font-weight: bold;
    border: 0px;
    padding: 15px 30px;
    border-radius: 25px;
    margin-top: 15%;
}
</style>