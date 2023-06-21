<script>

</script>

<template lang="">
    <div>
        <div class="container-blue">
            <div class="row">
                <ul>
                    <li>
                        <a href="#"><img src="../assets/buy-comics-digital-comics.png" alt="Img Digital Comic">DIGITAL COMICS</a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/buy-comics-merchandise.png" alt="Img Merch">DC MERCHANDISE</a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/buy-comics-subscriptions.png" alt="Img Sub">SUBSCRIPTION</a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/buy-comics-shop-locator.png" alt="Img Shop Location" id="locator">COMIC SHOP LOCATOR</a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/buy-dc-power-visa.svg" alt="Img Digital Comic" id="visa">DC POWER VISA</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../components/style/general' as *;
.container-blue{
    background-color: #0282f9;
    padding: 70px;
}
ul{
    list-style-type: none;
    display: flex;
    align-items: center;
    justify-content: space-around;
    li{
        display: flex;
        align-items: center;
        padding: 10px;
        &:hover{
            box-shadow: 0 0 5px 2px white;
            border-radius: 5%;
        }
        a{
            text-decoration: none;
            font-size: 15px;
            color: #fff;
            display: flex;
            align-items: center;
            img{
                width: 50px;
                margin-right: 15px;
            }
            #locator{
                height: 49px;
                width: 40px;
            }
            #visa{
                height: 49px;
            }
        }
    }
}
</style>