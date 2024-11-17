/*Home Page
Date LM: 17/11/2024
By: Daniel Acosta*/
<template>
    <form action="" method="post">
        <label for="restSearch">Search Vulpin</label>
        <input type="text" name="" id="restSearch" class="restSearch">
        <br>
        <br>
        <div id="filter">
            <input list="rating">
            <datalist id="rating">
                <option value="5"></option>
                <option value="4.5"></option>
                <option value="4"></option>
                <option value="3.5"></option>
                <option value="3"></option>
                <option value="2.5"></option>
                <option value="2"></option>
            </datalist>

            <input list="typeOfFood">
            <datalist id="typeOfFood">
                <option value="Any"></option>
                <option value="Mexican"></option>
                <option value="Japanese"></option>
                <option value="Chinese"></option>
                <option value="Indian"></option>
                <option value="French"></option>
                <option value="Thai"></option>
                <option value="Pizza"></option>
                <option value="Middle Eastern"></option>
                <option value="Italian"></option>
                <option value="Hamburger"></option>
                <option value="Vietnamese"></option>
                <option value="Seafood"></option>
                <option value="Other"></option>
            </datalist>
        </div>
    </form>
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

<style>

</style>