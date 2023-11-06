<script setup>
import HeaderNav from './HeaderNav.vue'
</script>
<template>
    <div class="top_part">
        <HeaderNav/>
        <div class="selected">
            <div id="selected_image">
                <img src="" alt="item_image">
            </div>
            <div id="selected_details">

            </div>

        </div>
    </div>


</template>

<style>
.top_part {
    padding: 0;
    margin: 0;
    height: 500px;
    background-color: #EFEEEE;
}
.selected {
    margin: 4%;
    display: grid;
    grid-template-columns: 2.5fr 1.5fr;
    /* 1fr and 3fr represent the 25% and 75% widths respectively */
    grid-gap: 10px; /* Adjust the gap between the columns */
    height: 80%;
}

#selected_details {
    background-color: lightgray;
    padding: 10px;
}

#selected_image {
    padding: 10px;
}

#selected_image img {
    width: 100%;
    /* Make sure the image fills its parent div */
}

</style>