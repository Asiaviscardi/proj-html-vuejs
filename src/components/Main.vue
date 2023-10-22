<script>
export default {
    name:'Main',
    data(){
        return{
            frase: 'We make your child happy day after day',
            frase2: 'Popular education for your child and you',
            descrizione: 'Teachers and parents around the world know that chess is not a simple game. It is a great learning tool that will help build your childs executive function skills.',
            ageGroup:'We provide chess classes to both children from 5 years old and adults.',
            chessVariants:'We dont only teach classical chess but also other top variants of this game.',
            chessPlayers:'Our alumni have won many prestigious chess tournaments in the country.',
            chessOpenings:'Our students know all the best chess openings and how to use them.'
        }
    }

}
</script>

<template>

    <div class="main-container">

        <div class="first-section">

            <div class="services-container">
                
                <h2>OUR SERVICES</h2>

                <P class="sottotitolo">{{ frase }}</P>

                <div class="card-container">

                    <div class="card-aside">

                        <h3>Chess Education</h3>

                        <p class="sottotitolo">{{ frase2 }}</p>

                        <p>{{ descrizione }}</p>

                        <ul>

                            <li>Build self-regulation and motivation</li>

                            <li>Help with concentration issues</li>

                            <li>Learn to plan, organize, and prioritize</li>

                            <li>Regulate emotions</li>

                            <li>Learn to play attention detail</li>

                        </ul>

                        <button>Learn More</button>

                    </div>
    
                    <div class="card">

                        <h4>Various Age groups</h4>

                        <p>{{ ageGroup }}</p>

                        <div class="card-down">

                           <h4>Best Chess Players</h4>

                           <p>{{ chessPlayers }}</p>

                        </div>

                    </div>

                    <div class="card">

                        <h4>Top Chess Variants</h4>

                        <p>{{ chessVariants }}</p>

                        <div class="card-down">
    
                            <h4>Best Chess Openings</h4>
    
                            <p>{{ chessOpenings }}</p>
    
                        </div>

                    </div>

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

        h2{
            text-align: center;
            font-size: xx-large;
        }

        .sottotitolo{
            font-size: 21px;
        }

        p{
            text-align: center;
            padding: 10px 0px;
        }

        .card-container{
            width: 100%;
            display: flex;
            flex-wrap: wrap;
            justify-content: end;
            padding: 10px;

            .card-aside{
                width: 25%;
                padding: 20px 0px;

                h3{
                    font-size: x-large;
                }

                p{
                    text-align: left;
                    line-height: 1.5;
                    padding-bottom: 20px;
                }

                li{
                    list-style: none;
                    line-height: 2;
                }

                button{
                    width: 120px;
                    background-color: #ffcd18;
                    text-align: center;
                    padding: 10px;
                    border-radius: 6px;
                    cursor: pointer;
                    border: none;
                    margin-top: 20px;
                }
            }

            .card{
                width: 30%;
                padding: 55px;
                line-height: 1.5;

                p{
                    text-align: left;
                }

                .card-down{
                    width: 100%;
                    padding-top: 90px;
                }
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