<script setup>

function buttonClick() {
    console.log("click!")
}

</script>

<template lang="pug">
    button.cool_button( @click="buttonClick" ) Требую нажатия
</template>

<style>
.cool_button {
    width: 20vw;
    height: 5vh;
    background-color: greenyellow;
    border-radius: 20px;
    border: none;
    font-size: 16px;
    font-family: sans-serif;
}

.cool_button:hover { 
    background-color: #40ca45;
}

.cool_button:active {
    background-color: #40ca45;
    transform: translateY(4px);
}
</style>