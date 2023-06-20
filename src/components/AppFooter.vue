<script>

</script>

<template>

    <div class="container_2">
        <div class="row">
            <img src="../assets/buy-comics-digital-comics.png" alt="">
            <div>DIGITAL COMICS</div>

            <img src="../assets/buy-comics-merchandise.png" alt="">
            <div>DC MERCHANDISE</div>

            <img src="../assets/buy-comics-subscriptions.png" alt="">
            <div>SUBSCRIPTION</div>

            <img id="shop-size" src="../assets/buy-comics-shop-locator.png" alt="">
            <div>COMIC SHOP LOCATOR</div>

            <img src="../assets/buy-dc-power-visa.svg" alt="">
            <div>DC POWER VISA</div>
        </div>
    </div>

    <div class="container">
        <div class="row">
            <div class="flex">
                <ul>
                    <li><h4>DC COMICS</h4></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                    <li><h4>SHOP</h4></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>

                <ul>
                    <li><h4>DC</h4></li>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>

                <ul>
                    <li><h4>SITES</h4></li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
            <div class="img"><img src="../../public/dc-logo-bg.png" alt=""></div>
        </div>
    </div>

</template>

<style lang="scss" scoped>
        .container_2{
        background-color: #0074E8;
        color: white;
        width: 100%;
        
        .row{
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 35px 0;

            img{
                width: 6%;
                margin-left: 30px;
            }

            div{
                margin-left: 10px;
                font-size: 12px;
            }

            #shop-size{
                width: 5%;
            }
        }
    }
    
    .container{
        background-image: url(../../public/footer-bg.jpg);
        .row{
            display: flex;
            justify-content: space-between;

            .flex{
                display: flex;
            }

            ul{
                padding: 40px 20px;

                li{
                    a{
                        color: gray;
                        font-size: 12px;
                    }
                    
                    h4{
                        color: white;
                        margin: 10px 0;
                        font-size: 20px;
                    }
                }
            }
        }
    }
</style>