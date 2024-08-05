<script setup>
import Card from './components/Card.vue';

const cardData = {
  user: {
    name: "Волков Иван Сергеевич",
  }
}
</script>

<template>
<div class="owner">
    <Card v-model="cardData"/>
</div>
</template>

<style>
.owner {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #999999;
}
</style>
