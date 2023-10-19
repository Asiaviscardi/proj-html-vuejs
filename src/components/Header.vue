<script>
export default {
    name:'Header',
    data(){
    return{
      indirizzo: '6767 Santa Monica Blvd, Los Angeles, CA 90038',
      numero: 'Call Now 123-456-7890'
    }
  }

}
</script>

<template>

    <div class="first-section">

        <div class="components-container">

            <div class="left">

                <p>{{indirizzo}}</p>

                <div class="img-container">

                    <img src="../assets/images/mt-2236-home-logo.png" alt="">

                </div>

            </div>

            <div class="right">

                <p>{{numero}}</p>

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

        <div class="jumbo">

            <div class="jumbo-components">

                jumbo

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
    background-color: rgba($color: #404040, $alpha: 0.2);

    .components-container{
        width: 80%;
        display: flex;

        .left{
            width: 50%;

            p{
                color: white;
                font-size: 12px;
                padding: 5px 0px;
            }

            .img-container{
                width: 100%;

                img{
                    width: 15%;
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
                padding: 5px 0px;
            }

            button{
                color: black;
                background: white;
                width: 100px;
                border: none;
                border-radius: 5px;
                cursor: pointer;
                margin: 8px 0px;
                padding: 6px;
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
    display: flex;
    justify-content: center;
    background-color: azure;

    .jumbo{
        width: 80%;
        display: flex;
        background-color: cornflowerblue;

        .jumbo-components{
            width: 50%;
            background-color: pink;
        }
    }
}

</style>