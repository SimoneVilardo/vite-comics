<script>
export default {
    data() {
        return {
            links:[
                {label: 'CHARACTERS', link:'#', active: false},
                {label: 'COMICS', link:'#', active: false},
                {label: 'MOVIES', link:'#', active: false},
                {label: 'TV', link:'#', active: false},
                {label: 'GAMES', link:'#', active: false},
                {label: 'COLLECTIBLES', link:'#', active: false},
                {label: 'VIDEOS', link:'#', active: false},
                {label: 'FANS', link:'#', active: false},
                {label: 'NEWS', link:'#', active: false},
                {label: 'SHOP', link:'#', active: false},
            ]
        }
    },
}

</script>

<template>
    <div class="container">
        <div class="row"> 
            <img src="../../public/dc-logo.png" alt="dc-logo">
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :href="link.link"> {{ link.label }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.row{
    display: flex;
    justify-content: space-between;
    img{
        width: 8%;
        margin: 15px 0;
    }
    
    ul{
        display: flex;

        li{
            display: flex;
            align-items: center;
            border: 5px solid white;
            
            &:hover{
                border-bottom: 5px solid #0282f9;
            }
            &:hover a{
                color: #0282f9;
            }
            
            a{
                cursor: pointer;
                margin: 10px;
                font-weight: 600;
                font-size: 12px;
            }

        }
    }

}
</style>