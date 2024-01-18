<script setup>
import {ref} from "vue";

const count = ref(0);
</script>
<template>
  <main>
  <div style = "text-align: center;">
    <h4>the current count is ...</h4>
    <h1>{{count}}</h1>
    <button @click="count--">-</button>
    <button @click="count++">+</button>
  </div>
</main>
</template>
<style scoped>
main{
  background-color:aliceblue;
  display: flex;
  justify-content: center;
}
</style>