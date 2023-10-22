<script>
export default {
    name:'Header',
    data(){
    return{
      indirizzo: '6767 Santa Monica Blvd, Los Angeles, CA 90038',
      numero: 'Call Now 123-456-7890',
      nome:'ACADEMIC CHESS FOR',
      descrizione:'We are dedicated to broadening and developing chess as art, recreation, and as a significant element of culture in Northern California.'
    }
  }

}
</script>

<template>

    <div class="first-section">

        <div class="components-container">

            <div class="left">

                <p>
                    
                    <svg xmlns="http://www.w3.org/2000/svg" height="10px" viewBox="0 0 384 512" > 
                        
                        <path xmlns="http://www.w3.org/2000/svg" d="M215.7 499.2C267 435 384 279.4 384 192C384 86 298 0 192 0S0 86 0 192c0 87.4 117 243 168.3 307.2c12.3 15.3 35.1 15.3 47.4 0zM192 128a64 64 0 1 1 0 128 64 64 0 1 1 0-128z" style="fill: #ffcd18;"/>
                    
                    </svg>
                    
                    {{indirizzo}}
                
                </p>

                <div class="img-container">

                    <img src="../assets/images/mt-2236-home-logo.png" alt="">

                </div>

            </div>

            <div class="right">

                <p>
                    <svg xmlns="http://www.w3.org/2000/svg" height="10px" viewBox="0 0 512 512" > 
                        
                        <path xmlns="http://www.w3.org/2000/svg" d="M164.9 24.6c-7.7-18.6-28-28.5-47.4-23.2l-88 24C12.1 30.2 0 46 0 64C0 311.4 200.6 512 448 512c18 0 33.8-12.1 38.6-29.5l24-88c5.3-19.4-4.6-39.7-23.2-47.4l-96-40c-16.3-6.8-35.2-2.1-46.3 11.6L304.7 368C234.3 334.7 177.3 277.7 144 207.3L193.3 167c13.7-11.2 18.4-30 11.6-46.3l-40-96z" style="fill: #ffcd18;"/>
                    
                    </svg>
                    
                    {{numero}}
                
                </p>

                <button>Donate</button>

                <div class="list-container">

                    <ul>
    
                        <li class="orange">Home</li>

                        <li>Services</li>

                        <li>Courses</li>

                        <li>About</li>

                        <li>FAQ</li>

                        <li>Blog</li>

                        <li>Contact Us</li>
    
                    </ul>

                </div>


            </div>

        </div>

    </div>

    <div class="second-section">

        <div class="button-container">

            <button>

                <svg xmlns="http://www.w3.org/2000/svg" height="25px" viewBox="0 0 512 512" > 
                        
                        <path xmlns="http://www.w3.org/2000/svg" d="M164.9 24.6c-7.7-18.6-28-28.5-47.4-23.2l-88 24C12.1 30.2 0 46 0 64C0 311.4 200.6 512 448 512c18 0 33.8-12.1 38.6-29.5l24-88c5.3-19.4-4.6-39.7-23.2-47.4l-96-40c-16.3-6.8-35.2-2.1-46.3 11.6L304.7 368C234.3 334.7 177.3 277.7 144 207.3L193.3 167c13.7-11.2 18.4-30 11.6-46.3l-40-96z" style="fill: #ffcd18;"/>
                    
                    </svg>

            </button>

        </div>

        <div class="jumbo">

            <div class="jumbo-components">

                <div class="welcome">Welcome</div>

                <h1>{{ nome }} <em>EVERYONE</em></h1>

                <p>{{ descrizione }}</p>

                <div class="buttons-container">

                    <button class="en-now">Enroll Now</button>
    
                    <button class="lea-more">Learn More</button>

                </div>


            </div>

        </div>
    </div>
  
</template>

<style scoped lang="scss">

.first-section{
    width: 100%;
    display: flex;
    justify-content: center;
    position: fixed;
    top: 0;
    z-index: 1000;
    background-color: rgba($color: #000000, $alpha: 0.2);

    .components-container{
        width: 70%;
        display: flex;

        .left{
            width: 50%;

            p{
                color: white;
                font-size: 12px;
                padding: 20px 0px;
            }

            .img-container{
                width: 100%;
                margin-bottom: 10px;

                img{
                    width: 20%;
                    padding: 15px 0px 5px;
                }
            }
        }

        .right{
            width: 50%;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;

            p{
                color: white;
                font-size: 12px;
                padding: 5px 160px;
            }

            button{
                color: black;
                background: white;
                width: 150px;
                border: none;
                border-radius: 10px;
                cursor: pointer;
                margin: 8px 0px;
                padding: 5px;
            }

            .list-container{
                width: 100%;
                margin: 0% 25%;

                ul{
                    list-style-type: none;
                    display: flex;
                    text-align: center;
                    

                    li{
                        padding-right: 12px;
                        cursor: pointer;
                        color: white;
                    }

                    .orange{
                        color: #ffcd18;
                    }
                }
            }
        }

    }
}

.second-section{
    width: 100%;
    height: 793px;
    display: flex;
    justify-content: center;
    background-image: url(../assets/images/mt-2236-home-bg1.jpg);
    background-size: contain;
    position: relative;
    padding-top: 70px;
    
    .button-container{
        width: 55px;
        display: flex;
        align-self: center;
        position: absolute;
        left: 0px;
        margin: 10px;

        button{
            width: 100%;
            height: 55px;
            border-radius: 50%;
            background-color: white;
            border: none;
            cursor: pointer;

        }
    }

    .jumbo{
        width: 70%;
        display: flex;

        .jumbo-components{
            width: 35%;
            padding: 150px 0px;

            .welcome{
                width: 100px;
                text-align: center;
                border-radius: 7px;
                background-color: #ffcd18;
            }

            h1{
                color: white;
                font-size: 49px;
                padding-top: 20px;

                em{
                    color: #ffcd18;
                }
            }

            p{
                color: white;
                padding: 20px 0px;
                line-height: 1.5;
            }

            .buttons-container{
                margin-top: 30px;

                .en-now{
                    width: 150px;
                    text-align: center;
                    background-color: #ffcd18;
                    padding: 10px;
                    margin-right: 5px;
                    border-radius: 6px;
                    cursor: pointer;
                    border: none;
    
                }
    
                .lea-more{
                    width: 150px;
                    text-align: center;
                    background-color: rgba($color: #000000, $alpha: 0);
                    color: white;
                    border: 1px solid white;
                    padding: 10px;
                    border-radius: 6px;
                    cursor: pointer;
    
                }
            }

        }
    }
}

</style>