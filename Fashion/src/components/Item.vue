<template>
    <div class="item">
        <div class="item_part" id="item_image">
            <img src="@/assets/images/Adidas Centennial 85 Low Clear Green _ Core White _ Easy Yellow.jpeg" alt="item">
        </div>
        <div class="item_part" id="item_details">
            <div id="name">
                <span>Nike shoes</span>
            </div>
            <div id="cost">
                <span>20$</span>
            </div>
        </div>
    </div>

</template>
<script>
</script>
<style>
.item {
  height: 300px;
  width: 310px;
  background-color: #EFEEEE;
  margin: 2%;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;

  /* 1fr and 3fr represent the 1:3 ratio */
}

.item_part img {
  display: block;
  width: 100%;
  height: 80%;
  /* background-color: black; */
  /* Make sure the image fills its parent div */
}

#item_details {
  position: absolute; 
  bottom: 0;
  width: 90%; 
  /* background-color: rgba(255, 255, 255, 0.8);  */
  display: flex;
  justify-content: space-between;
  padding: 10px;
  font-family: 'kedal',sans-serif;
}

@media(max-width: 767px) {
  .item {
    width: 155px;
    height: 130px;
    margin: 1%;
  }
}

</style>