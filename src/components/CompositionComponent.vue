<script setup>
const name = "muty learns vue 2"

const showName = () => {
  console.log(name)
}
</script>

<template>
  <h1>{{ name }}</h1>
  <button @click="showName">show name</button>
</template>