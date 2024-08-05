<script setup>
import SvgIcon from '@jamescoyle/vue-icon';
import { mdiFaceMan } from '@mdi/js'

const path = mdiFaceMan
const model = defineModel()
</script>

<template>
<div class="user">
    <svg-icon class="user__avatar" type="mdi" :path="path"></svg-icon>
    <div class="user__name">
        {{ model.name }}
    </div>
</div>
</template>
    
<style>
.user {
    display: flex;
}

.user__avatar {
    width: 50px;
    height: 50px;
}

.user__name {
    margin-top: 12px;
    margin-left: 10px;
    font-size: 24px;
    font-family: sans-serif;
}
</style>