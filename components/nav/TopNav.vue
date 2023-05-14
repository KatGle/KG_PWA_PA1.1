<template>
    <div class="nav">

       <div class="left-nav">
        <span><NuxtLink class="item" to="/">Home</NuxtLink></span>
        <span><NuxtLink class="item" to="/Button">Button</NuxtLink></span>
       </div>

    </div>
</template>

<script>

</script>
<style scoped>
.nav {
    display: flex;
    justify-content: flex-start;
    border: 5px solid #6a7ba678;
    background-color: #6568bb;
    border-bottom: 10px solid #00000055;
    box-shadow: 5px 5px 30px black;
    padding: 10px 15px;
    height: 100%;
    width: 100%;
    max-height: 40px;
    min-height: 30px;
    max-width: 1920px;
    min-width: 50px;
}

.left-nav {
    max-height: 120px;
    min-height: 100px;
    max-width: 120vw;
    min-width: 100px;
    color:white;
    text-decoration:none;
}

/* px, rem, em, vh, vw, % */
.item {
    font-size: 20px;
    font-family: monospace;
    text-decoration: none;
    padding: 20px;
    color: rgb(237, 166, 204);
    font-weight: bold;
    max-height: 120px;  
    min-height: 100px;
    max-width: 150px;
    min-width: 100px;
}


</style>