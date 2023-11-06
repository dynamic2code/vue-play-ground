<template>
    <div class="item">
        <div class="item_part" id="item_image">
            <img src="" alt="item">
        </div>
        <div class="item_part" id="item_details">
            <div id="name">
                <span>item name</span>
            </div>
            <div id="cost">
                <span>item cost</span>
            </div>
        </div>
    </div>

</template>
<script>
</script>
<style>
.item{
    height: 300px;
    /* width: 250px; */
    width: calc(50% -10px);
    background-color:#EFEEEE;
    margin: 2%;
    display: grid;
    grid-template-rows: 3fr 1fr;
    /* 1fr and 3fr represent the 1:3 ratio */
}
#item_image img {
    width: 100%;
    /* Make sure the image fills its parent div */
}

#item_details{
    padding: 10px;
    border: 1px solid black;
    display: flex;
    /* justify-content: center; */
    justify-content: space-between;
    align-items: center;
}
#name{
    float: left;
}
#cost{
    float: right;
}


</style>