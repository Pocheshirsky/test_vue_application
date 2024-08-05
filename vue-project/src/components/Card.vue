<script setup>
import User from './User.vue';
import CoolButton from './CoolButton.vue'

const model = defineModel()
</script>

<template>
<div class="card">
    <User class="card__user" v-model="model.user"/>
    <CoolButton class="card__button"/>
    <CoolButton class="card_button"/>
</div>
</template>

<style>
.card {
    height: 70vh;
    width: 70vw;
    background-color: white;
    border-radius: 24px;
}

.card__user {
    margin-left: 4vw;
    margin-top: 4vh;
}

.card__button {
    margin-top: 4vh;
    margin-left: 4vw;
}
</style>