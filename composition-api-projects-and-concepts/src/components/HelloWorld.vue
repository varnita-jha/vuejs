<!-- HTML -->
<template>
    <h1>This is a parent Component</h1>
    <AnotherComponent/>
</template>

<!-- CSS -->
<style>
    /* h1{
        color: red;
    } */
</style>

<!-- JS -->
<script setup>
    // console.log('Hello World')
    import AnotherComponent from './AnotherComponent.vue';
    
</script>

<!-- The order of the above (style, script or template doesn't matter)
    but the convention is:
    script -> template -> style
-->

<!-- A component inside another component is called nested component -->