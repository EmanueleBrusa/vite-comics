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
                        <a href="#"><img src="../assets/buy-comics-shop-locator.png" alt="Img Shop Location">COMIC SHOP LOCATOR</a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/buy-dc-power-visa.svg" alt="Img Digital Comic">DC POWER VISA</a>
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
        a{
            text-decoration: none;
            font-size: 15px;
            color: #fff;
            display: flex;
            align-items: center;
        }
    }
}
img{
    width: 50px;
    margin-right: 15px;
}
</style>