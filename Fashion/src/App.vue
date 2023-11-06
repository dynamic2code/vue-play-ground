<script setup>
import Header from './components/Header.vue'
import CategoryList from './components/CategoryList.vue'
import ItemList from './components/ItemList.vue'
</script>

<template>
  <header>
    <Header></Header>
  </header>
  <main>
    <CategoryList></CategoryList>
    <ItemList></ItemList>
  </main>

  <footer>

  </footer>

</template>

<style scoped>
header{
  padding: 0;
}
footer{
  
  width:100vw;
  height: 40px;
}
</style>
