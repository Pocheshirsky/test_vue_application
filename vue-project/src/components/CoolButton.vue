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
}

.cool_button:hover { 
    background-color: #3e8e41 
}

.cool_button:active {
    background-color: #3e8e41;
    transform: translateY(4px);
}
</style>