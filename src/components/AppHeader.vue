<script>
export default {
    data() {
        return {
            links: [
                {label: 'CHARACTERS', link: '#', active: false,},
                {label: 'COMICS', link: '#', active: false,},
                {label: 'MOVIES', link: '#', active: false,},
                {label: 'TV', link: '#', active: false,},
                {label: 'GAMES', link: '#', active: false,},
                {label: 'COLLECTIBLES', link: '#', active: false,},
                {label: 'VIDEOS', link: '#', active: false,},
                {label: 'FANS', link: '#', active: false,},
                {label: 'NEWS', link: '#', active: false,},
                {label: 'SHOP', link: '#', active: false,},
            ]
        }
    }
}
</script>

<template lang="">
    <div class="container">
        <div class="row">
            <img src="../../public/dc-logo.png" alt="Logo DC">
            <ul>
                <li v-for="(link, index) in links" :class="link.active ? 'active' : ''" :key="index">
                    <a :href="link.link">{{ link.label }}</a>
                </li>
            </ul>
        </div>    
    </div>
</template>

<style lang="scss" scoped>
.container{
    display: flex;
    justify-content: center;
    align-items: center;
}
.row{
    display: flex;
    justify-content: space-between;
    width: 80%;
    ul{
        list-style-type: none;
        display: flex;
        align-items: center;
        li{
            display: flex;
            align-items: center;
            padding: 10px;
            height: 100%;
            &:hover{
                border-bottom: 5px solid #0282f9;
                cursor: pointer;
            }
            a{
                text-decoration: none;
                font-size: 12px;
                font-weight :bold;
                color: black;
         
                &:hover{
                color: #0282f9;
            }
            }
            }
    }
    img{
        width: 100px;
        margin: 15px 0;
        &:hover{
            cursor:pointer;
        }
    }
}
</style>