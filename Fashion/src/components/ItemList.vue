<script setup>
import Item from './Item.vue'
</script>

<template>
    <div class="item_container">
        <div class="item_list">
            <Item></Item>
            <Item></Item>
            <Item></Item>
            <Item></Item>
            <Item></Item>
        </div>  
    </div>
</template>

<style>
.item_container{
    width: 100vw;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    height: 700px;
    overflow: auto;
}
.item_list{
    width: 80%;
    height: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    background-color: black;
}
</style>