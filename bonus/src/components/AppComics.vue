<script>
export default {
    props:{
        myComic: Object
    }
}
</script>
<template >
    <div class="fumetto">
        <img :src="myComic.thumb">
        <h4>{{ myComic.series }}</h4>
        <p><strong>Type: {{ myComic.type }}</strong></p>
    </div>
</template>
<style lang="scss" scoped>
    img{
        width: 200px;
        height: 200px;
        padding: 20px;
    }

    h4{
        padding: 0 20px;
    }

    p{
        padding: 0 20px;
        font-size: 10px;
    }
</style>