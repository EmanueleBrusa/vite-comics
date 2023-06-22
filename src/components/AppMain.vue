<script>

</script>

<template lang="">
<div id="jumbotron">

</div>
<div class="container">
    <div class="row">
        <h1>METTICI QUI LA ROBA PER DOMANI</h1>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use '../components/style/general' as *;
h1{
    color: white;
}
.container{
    background-color: black;
    display: flex;
    justify-content: center;
    padding: 50px;
    width: 100vw;
}
#jumbotron{
    background-image: url(../../public/jumbotron.jpg);
    width: 100%;
    height: 500px;
    background-size: cover;
    background-repeat: no-repeat;
}
</style>