<script>
export default {
  data(){
    return{
      name: "muty learns vue"
    }
  },
  methods: {
    showName(){
      console.log("option component result: ", this.name)
    }
  }
}
</script>

<template>
  <h1>{{ name }}</h1>
  <button @click="showName">show name</button>
</template>