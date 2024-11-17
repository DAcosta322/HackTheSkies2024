/*Home Page
Date LM: 16/11/2024
By: Daniel Acosta*/
<template>
    <div id="welcome">
        <h1>Welcome Back {{ name }}!!!</h1>
        <h2>INFO</h2>
    </div>

    <div id="ad1">
        <h2>Faster than Ever</h2>
        <img src="" alt="" srcset="">
    </div>
    <div id="ad2">
        <h2>Seemless Travel</h2>
        <img src="" alt="" srcset="">
    </div>
</template>

<script>
export default {
    data(){
        return{
            name: 'Home'
        }
    }
}
</script>

<style scoped>
#welcome{
    background-color: #000;
    align-content: center;
    justify-content: center;
    color: #ededed;
    font-size: 150;
    font-weight: 500;
    font-style: normal;
}
</style>