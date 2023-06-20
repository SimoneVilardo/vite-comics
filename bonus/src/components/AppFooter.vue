<script>

</script>

<template>

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
        </div>
    </div>
    <div class="container3">
        <div class="row">
            <button>SIGN-UP NOW!</button>
            <div class="icone">
                <h3>FOLLOW US</h3>
                <a href="#"><img src="../assets/footer-facebook.png" alt="facebook"></a>
                <a href="#"><img src="../assets/footer-twitter.png" alt="twitter"></a>
                <a href="#"><img src="../assets/footer-youtube.png" alt="youtube"></a>
                <a href="#"><img src="../assets/footer-pinterest.png" alt="pinterest"></a>
                <a href="#"><img src="../assets/footer-periscope.png" alt="periscope"></a>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>

.container{
background-image: url(../../public/footer-bg.jpg);
background-size: cover;
background-repeat: no-repeat;

.row{
    display: flex;
    justify-content: space-between;

    .flex{
        width: 100%;
        display: flex;
        background-image: url(../../public/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: right center;
    }

    ul{
        padding: 40px 0;

        li{
            line-height: 1.3rem;
            padding-right: 20px;
            a{
                color: gray;
                font-size: 12px;
            }
            
            h4{
                color: white;
                margin: 15px 0;
                font-size: 20px;
            }
        }
    }
}
}

.container3{
    background-color: #303030;
    width: 100%;
    padding: 30px 0;

    .row{
        display: flex;
        justify-content: space-between;
        button{
            background-color: #303030;
            border: 3px solid #0074E8;
            padding: 10px;
            color: white;
            font-size: 18px;
        }

        .icone{
            display: flex;
            align-items: center;
            h3{
                color: #0074E8;
                padding: 0 15px;
            }
            a{
                padding: 0 5px;
            }
        }
    }
    
}
</style>