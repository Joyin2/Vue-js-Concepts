<script>
import ArrayProps from '../components/ArrayProps.vue'

export default {
  components: {
    ArrayProps
  },
  data() {
    return {
      users: [
        { name: 'rohan', email: 'rohan@test.com' },
        { name: 'karan', email: 'karan@test.com' },
        { name: 'bjorn', email: 'bjorn@test.com' },
        { name: 'johnn', email: 'john@test.com' }
      ]
    }
  }
}
</script>

<template>
  <div class="container">
    <h1>hello app</h1>
    <!-- props -->
    <!-- <Home name="Joyin"/>   -->
    <ArrayProps v-bind:users="users" />
  </div>
</template>

<style scoped></style>
