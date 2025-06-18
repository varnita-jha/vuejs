<script setup>
const myMessage = 'Yellow World!';
const myNumber = 100;
function add(x, y) {
    return x + y
}
</script>

<template>
    <!-- Text Interpolation (shows dynamic texts) -->
    <h1>This is {{ myMessage }}</h1>
    <h2>My Number: {{ myNumber }}</h2>
    <h3>2 + 2 = {{ 2 + 2 }}</h3>
    <h1>Add two numbers (2 + 2): {{ add(2, 2) }}</h1>
    <!-- Note: we can't declare a variable or use if statement in Text Interpolation -->
</template>