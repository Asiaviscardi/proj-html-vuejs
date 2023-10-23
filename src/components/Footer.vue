<script>
export default {
    name:'Footer'

}
</script>

<template>

    <div class="footer-container">

        <div class="footer-components">

            <div class="card">

                <div class="img-container">
    
                    <img src="../assets/images/mt-2236-home-logo.png" alt="">
    
                </div>
    
                <p>Copyright &copy; 2021. All Rights Reserved.</p>

            </div>

            <div class="card">

                <p class="follow">Follow Us</p>

                <button class="icon">

                    <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 320 512">
                                    
                        <path d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z" style="fill: white;"/>
                                
                    </svg>
                    
                </button>

                <button class="icon">

                    <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 512 512">
                                    
                        <path d="M498.1 5.6c10.1 7 15.4 19.1 13.5 31.2l-64 416c-1.5 9.7-7.4 18.2-16 23s-18.9 5.4-28 1.6L284 427.7l-68.5 74.1c-8.9 9.7-22.9 12.9-35.2 8.1S160 493.2 160 480V396.4c0-4 1.5-7.8 4.2-10.7L331.8 202.8c5.8-6.3 5.6-16-.4-22s-15.7-6.4-22-.7L106 360.8 17.7 316.6C7.1 311.3 .3 300.7 0 288.9s5.9-22.8 16.1-28.7l448-256c10.7-6.1 23.9-5.5 34 1.4z" style="fill: white;"/>
                                            
                    </svg>

                </button>

                <button class="icon">

                    <svg xmlns="http://www.w3.org/2000/svg" height="15px" viewBox="0 0 448 512">
                                    
                        <path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z" style="fill: white;"/>
                                            
                    </svg>

                </button>

            </div>

            <div class="card">

                <p class="subscribe">Subscribe to get the latest news, course updates, discounts, events</p>

                <input type="email" placeholder="Enter your e-mail here *">

                <button>Subscribe</button>

            </div>


        </div>

    </div>
  
</template>

<style scoped lang="scss">

.footer-container{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: black;
    padding: 20px 0px;

    .footer-components{
        width: 70%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;

        .card{

            .img-container{
                margin-top: 30px;
                margin-bottom: 150px;
    
            }

            .follow{
                font-size: 20px;
                margin-bottom: 10px;
            }

            .icon{
                width: 50px;
                height: 50px;
                border: 1px solid white;
                background-color: black;
                cursor: pointer;
                padding: 2px;
                margin-right: 10px;
                border-radius: 6px;

            }

            .subscribe{
                margin: 20px 0px;
            }

            input{
                width: 100%;
                padding: 15px 20px;
            }

            button{
                width: 120px;
                height: 40px;
                background-color: #ffcd18;
                text-align: center;
                border-radius: 6px;
                cursor: pointer;
                border: none;
                font-weight: bold;
                margin-top: 20px;

            }

            
        }

    }
}

</style>