<script>
export default {
    name:'Main'

}
</script>

<template>

    <div class="main-container">

        <div class="first-section">

            <div class="services-container">
                
                services

            </div>

        </div>

        <div class="second-section">

            <div class="img-container">

                <div class="immagine">img</div>

                <div class="immagine">img</div>

                <div class="immagine">img</div>

                <div class="immagine">img</div>

            </div>

            <div class="learn">

                <div class="learn-components">learn</div>

            </div>

        </div>

        <div class="third-section">

            <div class="courses">courses</div>

        </div>

    </div>
  
</template>

<style scoped lang="scss">

.first-section{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: azure;

    .services-container{
        width: 80%;
        background-color: aqua;
    }
}

.second-section{
    width: 100%;
    background-color: azure;

    .img-container{
        width: 100%;
        display: flex;

        .immagine{
            width: 25%;
            border: 1px solid black;

        }
    }

    .learn{
        width: 100%;
        display: flex;
        justify-content: center;
        background-color: bisque;

        .learn-components{
            width: 80%;
            background-color: cornflowerblue;
        }
    }

}

.third-section{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: azure;

    .courses{
        width: 80%;
        background-color: pink;
    }
}

</style>