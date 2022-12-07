<template>
    <div class="container">
        
        <div class="column1">
            <div>
                <h3>ABOUT</h3>
            </div>
            
            <div class="text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis convallis ex ut sem accumsan vehicula. Integer elit arcu, hendrerit id sapien ut, facilisis accumsan arcu.
            </div>

            <div>
                <img src="../../assets/img/avada-movers-logo.png" alt="">
            </div>
        </div>

        <div class="column1">
            <div class="titolo">
                <h3>AVADA MOVERS</h3>
            </div>
            
            <div>
                <div class="indice">Home</div>
                <div class="indice">Rates</div>
                <div class="indice">Testimonials</div>
                <div class="indice">Blog</div>
                <div class="indice">Free Quote</div>
            </div>

            
        </div>

        <div class="column2">
            <div class="titolo">
                <h3>RECENT POSTS</h3>
            </div>
            
            <div>
                <ul>
                    <li>Heading Out To College?</li>
                    <li>Moving Your Business?</li>
                    <li>Outstanding Quality</li>
                    <li>Cost of Moving</li>
                    <li>Best Moving Tips</li>
                </ul>
            </div>

            
        </div>


    </div>



</template>

<script>

export default {
    name: 'AboutComp',
    

}


</script>



<style lang="scss" scoped>

.container{
    height: 48vh;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
}

.column1{
    width: 25%;
    height: 100%;
    line-height: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.column2{
    width: 20%;
    height: 100%;
    line-height: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.text{
    width: 80%;
    line-height: 30px;
    margin-top: 5%;
    font-weight: lighter;
    color: rgb(87, 86, 86);
    font-size: medium;
}

img{
    margin-top: 12%;
}

.indice{
    margin-top: 4%;
}

.titolo{
    padding-bottom: 5%;
}

li{
    list-style-type: none;
    margin-top: 5%;
}
</style>