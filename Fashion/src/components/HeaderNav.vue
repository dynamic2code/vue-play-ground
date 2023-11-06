<script>

</script>
<template>
    <div class="menu">
        <div class="menu_item">
            <img src="" alt="burger menu">
        </div>
        <div class="menu_item">
            <img src="" alt="back arrow">
            <span class="menutext">Back</span>
        </div>
        <div class="menu_item" id="heading">
            <span class="heading">shop name</span>
        </div>
        <div class="menu_item">
            <img src="" alt="cart">
            <span class="menutext">Cart</span>
        </div>
        <div class="menu_item">
            <span class="menutext">lang</span>
            <img src="" alt="down arrow">
            
        </div>
    </div>
</template>

<style>
.menu{
    display: flex;
    width: 100vw;
    height: 40px;
    background-color: #EFEEEE;
}
.menu_item{
    display: flex;
    width: auto;
    height: 100%;
    justify-content: center;
    align-items: center;
}
#heading{
    width: 300px;
    height: 100%;
}
</style>