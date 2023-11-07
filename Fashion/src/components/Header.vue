<script setup>
import HeaderNav from './HeaderNav.vue'
</script>
<template>
    <div class="top_part">
        <HeaderNav/>
        <div class="selected">
            <div id="selected_image">
                <img src="@/assets/images/Shoe_Porn__Alden_Leather_Bluchers-removebg-preview.png" alt="item_image">
            </div>
            <div id="selected_details">
                <div class="details_part">
                    <span class="heading">Shoes</span> <br>
                </div>
                <div class="details_part">
                    <span class="details">Welcome to our fashionable footwear haven! At Fashion Brand , we believe that every step you take should be a stylish one. Our meticulously curated shoe collection is designed to cater to every occasion, mood, and personality. From casual chic to glamorous elegance, our shoes are more than just accessories; they're statements of your unique style.</span>                    
                </div>
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
  src: url('~@/assets/fonts/koshy/otf/koshy-koshy-regular-400.otf');
}
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
    overflow: hidden;
}

#selected_details {
    /* background-color: lightgray; */
    padding: 10px;
    overflow: auto;
    
}

#selected_image {
    padding: 10px;
    height: 350px;
    display: flex;
    justify-content: center;
    align-items: center;
}

#selected_image img {
    object-fit: contain;
    /* Make sure the entire image fits inside the div without being squashed */
    width: 100%;
    height: 100%;
}
.details_part{
    height: auto;
    margin-bottom: 3%;
}
.heading{
    font-family: 'koshy',sans-serif;
    font-weight: 400;
}
.details{
    font-family: 'koshy',sans-serif;
    font-weight: 300;
}
@media (max-width: 767px) {
    #selected_image {
        padding: 10px;
        height: 200px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    #selected_image img {
        object-fit: contain;
        /* Make sure the entire image fits inside the div without being squashed */
        width: 100%;
        height: 100%;
    }
  .selected {
    margin: 4%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    grid-template-rows: 2.5fr 1.5fr; /* Set the rows in the same ratio as columns */
    grid-gap: 10px; /* Adjust the gap between the rows */
    height: 80%;
  }
}
</style>