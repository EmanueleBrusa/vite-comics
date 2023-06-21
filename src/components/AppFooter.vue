<script>

</script>

<template lang="">
    <div class="container">
        <div class="row">
            <div class="lists">
                <ul>  
                    <li><a href="#"><h4>DC COMICS</h4></a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#"><h4>SHOP</h4></a></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
                <ul>  
                    <li><a href="#"><h4>DC</h4></a></li>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy (new)</a></li>
                    <li><a href="#">AD Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscription</a></li>
                    <li><a href="#">Talent Workshop</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
                <ul>  
                    <li><a href="#"><h4>SITES</h4></a></li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
    </div>
    <div class="container-sub">
        <div class="row-sub">
            <div>
                <button class="sign-up">SIGN-UP NOW!</button>
            </div>
            <div class="social-media">
                <span class="follow-us">FOLLOW US</span>
                <a href="#"><img src="../../public/footer-facebook.png" alt="Facebook"></a>
                <a href="#"><img src="../../public/footer-twitter.png" alt="Facebook"></a>
                <a href="#"><img src="../../public/footer-youtube.png" alt="Facebook"></a>
                <a href="#"><img src="../../public/footer-pinterest.png" alt="Facebook"></a>
                <a href="#"><img src="../../public/footer-periscope.png" alt="Facebook"></a>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../components/style/general' as *;
.container{
    background-image: url(../../public/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
}
ul{
    list-style-type: none;
    padding: 50px 30px 40px 0;

    li{
        line-height: 1.5rem;
        h4{
            font-size: 20px;
            color: #fff;
            margin: 15px 0;
        }

        a{
            color: #959595;
            text-decoration: none;
            font-size: 13px;
            font-weight: 400;
        }
        &:hover{
            text-decoration: underline;
            color: white;
        }
    }
}
.lists{
    display: flex;
    gap: 40px;
    width: 100%;
    background-image: url(../../public/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right center;
}

.container-sub{
    width: 100%;
    background-color: #303030;
    .row-sub{
        display: flex;
        justify-content: space-around;
        padding: 30px;
        .sign-up{
            font-size: 15px;
            font-weight: 700;
            color: white;
            border:solid #0282f9;
            padding: 20px;
            background: #303030;
            &:hover{
                box-shadow: 0 0 5px 2px #0282f9;
                cursor: pointer;
            }
        }
        .social-media{
            display: flex;
            gap: 20px;
            align-items: center;
            .follow-us{
                font-size: 20px;
                font-weight: 700;
                color: #0282f9;
                padding: 20px;
            }
            img:hover{
                box-shadow: 0 0 10px 2px #0282f9;
                cursor: pointer;
                border-radius: 50%;
            }
        }
    }
}

</style>