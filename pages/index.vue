<template>
    <div class="container-beni">
        <div @click="increment()" >hey beni</div>
        <div :style="{transform: `scale${increment}`}">{{counter}}</div>
    </div>
</template>

<script setup>
const counter = ref(0)
const increment = () => counter.value++
</script>

<style scoped>
.container-beni {
    background-color: red;
}
</style>