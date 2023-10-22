<script>
export default {
    name:'Main',
    data(){
        return{
            frase: 'We make your child happy day after day'
        }
    }

}
</script>

<template>

    <div class="main-container">

        <div class="first-section">

            <div class="services-container">
                
                <h2>OUR SERVICES</h2>

                <P>{{ frase }}</P>

                <div class="card-container">

                    <div class="card-aside">card aside</div>
    
                    <div class="card">r</div>
                    <div class="card">t</div>
                    <div class="card">r</div>
                    <div class="card">rt</div>
                </div>


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

        <div class="fourth-section">

            <div class="step">step</div>

        </div>

        <div class="fifth-section">

            <div class="events">events</div>

        </div>

        <div class="sixth-section">

            <div class="news">news</div>

        </div>

    </div>
  
</template>

<style scoped lang="scss">

.first-section{
    width: 100%;
    display: flex;
    justify-content: center;

    .services-container{
        width: 70%;
        margin-top: 50px;
        background-color: aqua;

        h2{
            text-align: center;
        }

        p{
            color: lightgrey;
            text-align: center;
            padding: 10px 0px;
        }

        .card-container{
            width: 100%;
            background-color: coral;
            display: flex;
            flex-wrap: wrap;
            justify-content: end;

            .card-aside{
                width: 30%;
                background-color: cadetblue;
            }

            .card{
                width: 35%;
                background-color: darkkhaki;
                border: 1px solid black;
                justify-self: end;
            }
        }

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
            width: 70%;
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
        width: 70%;
        background-color: pink;
    }
}

.fourth-section{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: azure;

    .step{
        width: 70%;
        background-color: cornflowerblue;
    }

}

.fifth-section{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: azure;

    .events{
        width: 70%;
        background-color: pink;
    }

}

.sixth-section{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: azure;

    .news{
        width: 70%;
        background-color: cornflowerblue;
    }

}
</style>