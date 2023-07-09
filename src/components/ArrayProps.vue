<script>
export default {
  props: ['users']
}
</script>

<template>
  <div>
    <h1>Child</h1>
    <div>
      <table border="1">
        <tr>
          <td><h1>Name</h1></td>
          <td><h1>Email</h1></td>
        </tr>
        <tr v-for="user in users" :key="user.email">
          <td>{{ user.name }}</td>
          <td>{{ user.email }}</td>
        </tr>
      </table>
    </div>
  </div>
</template>
