<script>
export default {
  methods: {
    hello: () => {
      alert('hello, thank you for click')
    }
  }
}
</script>

<template>
    <button v-on:click="hello">click here</button>
</template>
