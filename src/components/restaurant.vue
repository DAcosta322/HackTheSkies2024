/*Restaurant Token
Date LM: 17/11/2024
By: Daniel Acosta*/
<template>
    <img v-bind:src="url" width="25vw" height="25vw">
    <h3 id="name">{{ rName }}</h3>
    <div id="flex">
        <h3 id="rating">{{ rating }}</h3>
        <h3 id="distance">{{ distance }}</h3>
    </div>
</template>

<script>
export default {
    data(){
        return{
            name: "restaurant",
            url: 'https://s7d1.scene7.com/is/image/mcdonaldsstage/DC_202307_8936_EVM_M_BigMac_Coke_1564x1564:product-header-mobile?wid=1313&hei=1313&dpr=off'
        }
    }
};
</script>

<style lang="css" scoped>
#name{
    color: #000;
    font-family: "Iceland", sans-serif;
    font-size: 120;
    font-weight: 300;
    font-style: normal;
}

#rating{
    color: #000;
    font-family: "Iceland", sans-serif;
    font-size: 100;
    font-weight: 300;
    font-style: normal;
}

#distance{
    color: #000;
    font-family: "Iceland", sans-serif;
    font-size: 100;
    font-weight: 250;
    font-style: normal;
}

#flex{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: baseline;
}
</style>