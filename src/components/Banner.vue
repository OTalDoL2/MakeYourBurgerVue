<template>
    <div id="main-banner">
        <h1>Make Your Burguer</h1>
    </div>
</template>
<!-- <img :src="logo" :alt="alt" id="logo"></img> -->
<script>
    export default{
        name: "banner",
        // props: [image]
    }
</script>

<style scoped>
    #main-banner{
        background-image: url("../../public/img/burger.jpg");
        background-position: 0 -250px;
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    #main-banner h1{
        color: #fff;
        font-size: 60px;
        background-color: rgb(34, 34, 34);
        padding: 10px 20px;
    }
</style>