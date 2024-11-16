/*Home Page
Date LM: 16/11/2024
By: Daniel Acosta*/
<template>
    <div class="header">
        <h1 id="title">VULPIN</h1>
        <h2 class="slogan">Faster Than You Thought</h2>

        <div class="choices">
            <div class="headItem">Home</div>
            <div class="headItem">Order</div>
            <div class="headItem">Profile</div>
            <div class="headItem">Temp</div>
        </div>
    </div>
</template>


<script>
export default {
    data(){
        return{
            name:'Header'
        }
    }
};
</script>


<style Scoped>
    .header{
        background-image: linear-gradient(#87ceeb, #07e6fa);
    }
    .choices{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-around;
        align-items: baseline;
    }
    .headItem{
        color: #ededed;
        font-family: "Iceland", sans-serif;
        font-size: 100;
        font-weight: 300;
        font-style: normal;
    }
    #title{
        color: #ededed;
        font-size: 150;
        font-weight: 500;
        font-style: normal;
    }
    #slogan{
        color: #ededed;
        font-size: 72;
        font-weight: 300;
        font-style: normal;
    }
</style>