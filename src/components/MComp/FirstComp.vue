<template>

    <div class="container">
        <div class="textG">HEADACHE FREE</div>
        <div class="titleV">Award Winning Moving Company</div>
        <div class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac augue. Orci varius natoque penatibus et magnis dis parturient montes, ridiculus mus. Aliquam enim leo, condimentum facilisis nulla sed, cursus arcu. Aliquam enim leo.</div>
        <div>
            <button>READ OUR TESTIMONIALS</button>
        </div>
    </div>


</template>

<script>

export default {
    name: 'FirstComp'
}

</script>

<style lang="scss" scoped>

.container{
    height: 660px;
    background-color: rgb(242, 245, 248);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.textG{
    color: rgb(75, 74, 74);
    font-weight: bold;
    margin-top: 1%;
}

.titleV{
    color: rgb(106, 191, 22);
    font-size: 45px;
    font-weight: bolder;
    width: 20%;
    margin-top: 1%;
    
}

.text{
    width: 40%;
    line-height: 30px;
    margin-top: 1%;
    font-weight: lighter;
    color: rgb(87, 86, 86);
}

button{
    margin-top: 15%;
    padding: 15px 30px;
    font-weight: bolder;
    color: white;
    border: 0;
    background-color: rgb(22, 117, 191);
    border-radius: 30px;
}

</style>