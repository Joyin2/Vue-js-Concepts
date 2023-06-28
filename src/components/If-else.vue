<script>
export default {
  data() {
    return {
      show: false
    }
  },

  methods: {
    display() {
      this.show = !this.show
    }
  }
}
</script>
<template>
  <div>
    <h1 v-if="show">it's true bro</h1>
    <h1 v-else>it's false bro</h1>
    <button v-on:click="display">Toggle</button>
  </div>
</template>
