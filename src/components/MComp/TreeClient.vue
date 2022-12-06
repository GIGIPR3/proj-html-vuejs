<template>

    <div class="container">

        <div class="card">

            <div class="foto"></div>

            <div class="titleB">
                John Doe
            </div>

            <div class="text">
                <i>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus
                    et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</i>
            </div>
        </div>

        <div class="card">

            <div class="foto"></div>

            <div class="titleB">
                John Doe
            </div>

            <div class="text">
                <i>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus
                    et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</i>
            </div>
        </div>

        <div class="card">

            <div class="foto"></div>

            <div class="titleB">
                John Doe
            </div>

            <div class="text">
                <i>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus
                    et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</i>
            </div>
        </div>

    </div>



</template>

<script>

export default {
    name: 'TreeClient'

}

</script>

<style lang="scss" scoped>

.foto {
    height: 150px;
    width: 150px;
    border-radius: 50%;
    background-color: aqua;
}

.card {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.titleB {
    color: rgb(22, 117, 191);
    font-weight: bold;
    font-size: x-large;
    margin-top: 3%;
}

.text {
    width: 80%;
    line-height: 30px;
    margin-top: 3%;
    font-weight: lighter;
    color: rgb(87, 86, 86);
}
</style>