<template>
  <p>{{ message }}</p>
  <button @click="helloWorld">Click me and see the console</button>
</template>

<script setup>
const message = "This is a paragraph inside the MessageCard component";

function helloWorld() {
  console.log("Hello World");
}
</script>
