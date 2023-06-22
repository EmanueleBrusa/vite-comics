<script>
export default {
    props:{
        mybooks: Object
    }
}
</script>

<template>
    <div class="card">
        <img :src="mybooks.thumb">
        <h4>{{ mybooks.series }}</h4>
        <p><strong>Type: {{ mybooks.type }}</strong></p>
    </div>
</template>

<style lang="sccss" scoped>

</style>