<template>
    <div id="secure">
        <img src="../static/img/user.png" alt="user">
        <h1>Имя Фамилия</h1>
        <p id="email"></p>
    </div>
</template>

<script>
    export default {
        name: 'Secure',
        data() {
            return {};
        }
    }
</script>

<style>
#secure {
         width: 900px;
		margin: 0px auto;
		background-color: #839d8f;
    }
img {
    float: left;
    margin-right: 30px;
    width: 300px;
    height: 300px;
}
</style>