<template>

    <div class="container">

        <div class="card">
            <div class="CardImage"></div>

            <div class="contenuto">

                <div class="titleB">
                    <!-- {{ card.titolo }} --> We Do All The Lifting
                </div> 

                <div class="text">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                </div>

                <div>
                    <button>READ MORE</button>
                </div>

            </div>
        </div>

        <div class="card">
            <div class="CardImage1"></div>

            <div class="contenuto">

                <div class="titleB">
                    <!-- {{ card.titolo }} --> We Do All The Lifting
                </div> 

                <div class="text">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                </div>

                <div>
                    <button>READ MORE</button>
                </div>

            </div>
        </div>

        <div class="card">
            <div class="CardImage2"></div>

            <div class="contenuto">

                <div class="titleB">
                     We Do All The Lifting
                </div> 

                <div class="text">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                </div>

                <div>
                    <button>READ MORE</button>
                </div>

            </div>
        </div>


    </div>




</template>



<script>

export default {
    name: 'ThreeCard',
    data() {
    return {
      card: [
        {
          titolo: 'Two Man Teams',
          testo: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.'
        },
        {
          titolo: 'We Do All The Lifting',
          testo: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.'
        },
        {
          titolo: 'Coast To Coast',
          testo: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.'
        }
      ]
    }
  }
}




</script>



<style lang="scss" scoped>
.container {
    height: 30px;
    /*     background-color: aqua; */
/*     display: flex; */
/*     flex-direction: row; */
}

.card {
    height: 100%;
    width: 21%;
    /*     background-color: antiquewhite; */
    border: 20px solid rgb(242, 245, 248);
    margin: 1%;
}

.CardImage {
    background-image: url(../../assets/img/avada-movers-serviceonephoto-final.jpg);
    background-size: cover;
    background-position: bottom;
    height: 45%;
    border-bottom: 20px solid rgb(242, 245, 248);
}

.CardImage1 {
    background-image: url(../../assets/img/avada-movers-servicetwophoto-final-400x255.jpg);
    background-size: cover;
    background-position: bottom;
    height: 45%;
    border-bottom: 20px solid rgb(242, 245, 248);
}

.CardImage2 {
    background-image: url(../../assets/img/avada-movers-servicethreephoto-final.jpg);
    background-size: cover;
    background-position: bottom;
    height: 45%;
    border-bottom: 20px solid rgb(242, 245, 248);
}


.titleB {
    color: rgb(22, 117, 191);
    font-weight: bold;
    font-size: x-large;
    margin-top: 4%;
}

.contenuto{
/*     height: 100%; */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    line-height: 30px;
    text-align: center;
    padding: 3%;
    
}

.text{
/*     width: 40%;
    line-height: 30px; */
    margin-top: 4%;
    font-weight: lighter;
    color: rgb(87, 86, 86);
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



</style>

