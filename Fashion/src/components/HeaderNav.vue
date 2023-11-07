<script>

</script>
<template>
    <div class="menu">
        <div id="left">
            <div class="menu_item">
                <img src="@/assets/images/menu.png" alt="burger menu">
            </div>
            <div class="menu_item">
                <img src="@/assets/images/left.png" alt="back arrow">
                <span class="menutext">Back</span>
            </div> 
        </div>

        <div id="center">
            <div class="menu_item" id="heading">
                <span class="heading">shop name</span>
            </div>
        </div>



        <div id="right">
            <div class="menu_item">
                <img src="@/assets/images/grocery-store.png" alt="cart">
                <span class="menutext">Cart</span>
            </div>
            <div class="menu_item">
                <span class="menutext">lang</span>
                <img src="@/assets/images/down.png" alt="down arrow">
                
            </div>            
        </div>

    </div>
</template>

<style>
@font-face {
  font-family: 'kedal'; /* Font family name to be used in your styles */
  src: url('~@/assets/fonts/kedal/otf/kedal-kedal-regular-400.otf');
}
@font-face {
  font-family: 'koshy'; /* Font family name to be used in your styles */
  src: url('~@/assets/fonts/koshy/ttf/koshy-koshy-regular-400.ttf');
}

.menu {
    padding: 0;
    margin: 0;
    display: flex;
    width: 100%;
    height: 40px;
    background-color: #EFEEEE;
    justify-content: space-between; /* Aligns children divs to the start and end */
    align-items: center; /* Centers the content vertically */
    font-family: 'koshy',sans-serif;
    font-weight: 300;
}

#left, #right, #center {
    display: flex;
    align-items: center; /* Centers the content vertically within each div */
}

.menu_item {
    display: flex;
    height: 100%;
    align-items: center; /* Centers the content vertically within menu items */
    /* background-color: blueviolet; */
    margin-right: 2%;
    padding: 0 10px; /* Add padding to menu items for spacing */
    
}

.menu_item img {
    width: 20px;
    height: 20px;
    margin-right: 5px; /* Add some spacing between icon and text */
}

#heading {
    width: 100px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
@media(max-width: 767px) {
    #heading {
        width: 100px;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .menu_item {
        display: flex;
        height: 100%;
        align-items: center; /* Centers the content vertically within menu items */
        /* background-color: blueviolet; */
        margin-right: 2%;
        padding: 0 1px; /* Add padding to menu items for spacing */
    }
}

/* Add additional styles for .menutext and .heading if needed */

</style>