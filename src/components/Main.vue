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
            chessOpenings:'Our students know all the best chess openings and how to use them.',
            cours1:'Learn the tips, tricks, and strategies from one of the best masters',
            cours2:'Catered to adult beginners who have a few hours a week to pratice',
            cours3:'Chess lessons for children and adults held completely online'
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

                            <li>

                                <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 320 512">
                                    
                                    <path d="M215.5 224c29.2-18.4 48.5-50.9 48.5-88c0-57.4-46.6-104-104-104S56 78.6 56 136c0 37.1 19.4 69.6 48.5 88H96c-17.7 0-32 14.3-32 32c0 16.5 12.5 30 28.5 31.8L80 400H240L227.5 287.8c16-1.8 28.5-15.3 28.5-31.8c0-17.7-14.3-32-32-32h-8.5zM22.6 473.4c-4.2 4.2-6.6 10-6.6 16C16 501.9 26.1 512 38.6 512H281.4c12.5 0 22.6-10.1 22.6-22.6c0-6-2.4-11.8-6.6-16L256 432H64L22.6 473.4z" style="fill: #ffcd18;"/>
                                
                                </svg>
                                
                                Build self-regulation and motivation
                            
                            </li>

                            <li>

                                <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 320 512">
                                
                                    <path d="M215.5 224c29.2-18.4 48.5-50.9 48.5-88c0-57.4-46.6-104-104-104S56 78.6 56 136c0 37.1 19.4 69.6 48.5 88H96c-17.7 0-32 14.3-32 32c0 16.5 12.5 30 28.5 31.8L80 400H240L227.5 287.8c16-1.8 28.5-15.3 28.5-31.8c0-17.7-14.3-32-32-32h-8.5zM22.6 473.4c-4.2 4.2-6.6 10-6.6 16C16 501.9 26.1 512 38.6 512H281.4c12.5 0 22.6-10.1 22.6-22.6c0-6-2.4-11.8-6.6-16L256 432H64L22.6 473.4z" style="fill: #ffcd18;"/>
                                
                                </svg>
                                
                                Help with concentration issues
                            
                            </li>

                            <li>

                                <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 320 512">
                                    
                                    <path d="M215.5 224c29.2-18.4 48.5-50.9 48.5-88c0-57.4-46.6-104-104-104S56 78.6 56 136c0 37.1 19.4 69.6 48.5 88H96c-17.7 0-32 14.3-32 32c0 16.5 12.5 30 28.5 31.8L80 400H240L227.5 287.8c16-1.8 28.5-15.3 28.5-31.8c0-17.7-14.3-32-32-32h-8.5zM22.6 473.4c-4.2 4.2-6.6 10-6.6 16C16 501.9 26.1 512 38.6 512H281.4c12.5 0 22.6-10.1 22.6-22.6c0-6-2.4-11.8-6.6-16L256 432H64L22.6 473.4z" style="fill: #ffcd18;"/>
                                
                                </svg>
                                
                                Learn to plan, organize, and prioritize
                            
                            </li>

                            <li>

                                <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 320 512">
                                    
                                    <path d="M215.5 224c29.2-18.4 48.5-50.9 48.5-88c0-57.4-46.6-104-104-104S56 78.6 56 136c0 37.1 19.4 69.6 48.5 88H96c-17.7 0-32 14.3-32 32c0 16.5 12.5 30 28.5 31.8L80 400H240L227.5 287.8c16-1.8 28.5-15.3 28.5-31.8c0-17.7-14.3-32-32-32h-8.5zM22.6 473.4c-4.2 4.2-6.6 10-6.6 16C16 501.9 26.1 512 38.6 512H281.4c12.5 0 22.6-10.1 22.6-22.6c0-6-2.4-11.8-6.6-16L256 432H64L22.6 473.4z" style="fill: #ffcd18;"/>
                                
                                </svg>
                                
                                Regulate emotions
                            
                            </li>

                            <li>

                                <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 320 512">
                                    
                                    <path d="M215.5 224c29.2-18.4 48.5-50.9 48.5-88c0-57.4-46.6-104-104-104S56 78.6 56 136c0 37.1 19.4 69.6 48.5 88H96c-17.7 0-32 14.3-32 32c0 16.5 12.5 30 28.5 31.8L80 400H240L227.5 287.8c16-1.8 28.5-15.3 28.5-31.8c0-17.7-14.3-32-32-32h-8.5zM22.6 473.4c-4.2 4.2-6.6 10-6.6 16C16 501.9 26.1 512 38.6 512H281.4c12.5 0 22.6-10.1 22.6-22.6c0-6-2.4-11.8-6.6-16L256 432H64L22.6 473.4z" style="fill: #ffcd18;"/>
                                
                                </svg>
                                
                                Learn to play attention detail
                            
                            </li>

                        </ul>

                        <button>Learn More</button>

                    </div>
    
                    <div class="card">

                        <img src="../assets/images/mt-2236-home-icon1.png" alt="">

                        <h4>Various Age groups</h4>

                        <p>{{ ageGroup }}</p>

                        <div class="card-down">

                            <img src="../assets/images/mt-2236-home-icon3.png" alt="">

                           <h4>Best Chess Players</h4>

                           <p>{{ chessPlayers }}</p>

                        </div>

                    </div>

                    <div class="card">

                        <img src="../assets/images/mt-2236-home-icon2.png" alt="">

                        <h4>Top Chess Variants</h4>

                        <p>{{ chessVariants }}</p>

                        <div class="card-down">

                            <img src="../assets/images/mt-2236-home-icon4.png" alt="">
    
                            <h4>Best Chess Openings</h4>
    
                            <p>{{ chessOpenings }}</p>
    
                        </div>

                    </div>

                </div>


            </div>

        </div>

        <div class="second-section">

            <div class="img-container">

                <div class="immagine">

                    <img src="../assets/images/mt-2236-home-gallery1.jpg" alt="">

                </div>

                <div class="immagine">

                    <img src="../assets/images/mt-2236-home-gallery2.jpg" alt="">

                </div>

                <div class="immagine">

                    <img src="../assets/images/mt-2236-home-gallery3.jpg" alt="">

                </div>

                <div class="immagine">

                    <img src="../assets/images/mt-2236-home-gallery4.jpg" alt="">

                </div>

            </div>

            <div class="learn">

                <div class="learn-components">

                    <img src="../assets/images/mt-2236-home-icon5.png" alt="">

                    <div>

                        <h2>PLAY & LEARN</h2>
    
                        <p>Take a look into our day to day life here at Chees School</p>

                    </div>

                    <button>Learn More</button>

                </div>

            </div>

        </div>

        <div class="third-section">

            <div class="courses">

                <div>

                    <h2>Courses</h2>
    
                    <p>To keep up with the constantly rising standards of play</p>

                </div>

                <div class="card-container">

                    <div class="card">

                        <div class="img-container">

                            <img src="../assets/images/mt-2236-home-img1.jpg" alt="">

                        </div>


                        <h3>Garry Kasparov's Masterclass</h3>

                        <p>{{ cours1 }}</p>

                        <h3>$456</h3>

                        <button>View More</button>

                    </div>
    
                    <div class="card middle">

                        <div class="img-container">

                            <img src="../assets/images/mt-2236-home-img2.jpg" alt="">

                        </div>

                        <h3>Online Chess Lessons for Beginners</h3>

                        <p>{{ cours2 }}</p>

                        <h3>$205</h3>

                        <button>View More</button>


                    </div>
    
                    <div class="card">

                        <div class="img-container">

                            <img src="../assets/images/mt-2236-home-img3.jpg" alt="">

                        </div>

                        <h3>International Chess School Online</h3>

                        <p>{{ cours3 }}</p>

                        <h3>$356</h3>

                        <button>View More</button>


                    </div>

                </div>

                <button>View Other Courses</button>

            </div>

        </div>

        <div class="fourth-section">

            <div class="step">

                <div>

                    <h2>TAKE THE<span class="orange">FIRST STEP</span></h2>
    
                    <p>The fascinating world of chess has its doors open for anyone</p>

                </div>

                <button>View More</button>

            </div>

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
    margin-bottom: 50px;

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

            .card-aside{
                width: 35%;
                padding: 20px 0px;

                h3{
                    font-size: x-large;
                    padding-top: 60px;
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
                    width: 150px;
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
                    padding-top: 55px;
                }
            }
        }

    }
}

.second-section{
    width: 100%;

    .img-container{
        width: 100%;
        display: flex;

        .immagine{
            width: 25%;

            img{
                width: 100%;
                height: 100%;
            }

        }
    }

    .learn{
        width: 100%;
        display: flex;
        justify-content: center;
        background-color: #ffcd18;

        .learn-components{
            width: 70%;
            padding: 20px 100px;
            display: flex;
            justify-content: space-between;
            align-items: center;

            img{
                width: 70px;
            }

            h2{
                padding-bottom: 15px;
            }

            button{
                width: 150px;
                background-color: #ffcd18;
                text-align: center;
                padding: 10px;
                border-radius: 6px;
                cursor: pointer;
            }
        }
    }

}

.third-section{
    width: 100%;
    display: flex;
    justify-content: center;

    .courses{
        width: 70%;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        padding-top: 60px;

        h2{
            text-align: center;
        }

        p{
            padding: 10px;
        }

        .card-container{
            width: 100%;
            display: flex;
            margin: 20px 0px;
            .card{
                width: calc(100%/3);
                display: flex;
                flex-direction: column;
                align-items: center;
                box-shadow: 5px 10px 10px #e8e8e8;

                .img-container{
                    width: 100%;


                    img{
                        width: 100%;
                        height: 100%;
                    }
                }

                h3{
                    text-align: center;
                    padding: 25px 0px;
                }

                p{
                    text-align: center;
                    line-height: 1.5;
                    padding: 0px 85px;
                }

                button{
                    width: 150px;
                    background-color: #ffcd18;
                    text-align: center;
                    padding: 10px;
                    border-radius: 6px;
                    cursor: pointer;
                    border: none;
                    margin-bottom: 20px;
                }
                

            }

            .middle{
                    margin: 0px 30px;
            }
        }

        button{
            width: 190px;
            text-align: center;
            padding: 10px;
            border-radius: 6px;
            cursor: pointer;
            background-color: white;
            margin: 30px 0px;
            font-weight: bold;
        }


    }
}

.fourth-section{
    width: 100%;
    display: flex;
    justify-content: center;
    background-image: url(../assets/images/mt-2236-home-bg2.jpg);
    background-size: cover;

    .step{
        width: 70%;
        display: flex;
        justify-content: space-between;
        padding: 80px 0px;

        h2{
            color: white;
            font-size: xx-large;
            padding-bottom: 15px;
        }

        .orange{
            color: #ffcd18;
            padding-left: 10px;
        }

        p{
            color: white;
        }

        button{
            width: 150px;
            height: 35px;
            background-color: #ffcd18;
            text-align: center;
            border-radius: 6px;
            cursor: pointer;
            border: none;

        }
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