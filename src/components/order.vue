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
                <option value="5">
                <option value="4.5">
                <option value="4">
                <option value="3.5">
                <option value="3">
                <option value="2.5">
                <option value="2">
            </datalist>
        </div>
    </form>
</template>

<script>
export default {

}
</script>

<style>

</style>