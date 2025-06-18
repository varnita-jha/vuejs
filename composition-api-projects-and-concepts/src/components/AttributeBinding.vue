<script setup>
// const myChannel = "https://youtu.be/pgWZLS75Nmo?si=JRNHQ7aHxSC08kYN";
const campus = 'C:/Users/IN0VMJH/Downloads/College Campus.jpg'
const imageWidth = 400;
const imageHeight = 400;
</script>

<template>
    <!-- <a v-bind:href = "myChannel">VueJs Tutorial with Projects</a> -->
    <!-- <a :href="myChannel">VueJs Tutorial with Projects</a> -->
    <!-- the above 2 examples give same output (so "v-bind" keyword in not necessary for this (just ":" works)) -->
    <img :src="campus" alt="campus photo" :width="imageWidth" :height="imageHeight"/>
</template>