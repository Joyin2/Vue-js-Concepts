<script>
export default {
  data() {
    return {
      users: [
        { id: 1, name: 'joyin', email: 'joyin@gmail.com' },
        { id: 2, name: 'peter', email: 'peter@gmail.com' },
        { id: 3, name: 'ragnar', email: 'ragnar@gmail.com' },
        { id: 4, name: 'bjorn', email: 'bjorn@gmail.com' }
      ]
    }
  }
}
</script>

<template>
  <div>
    <h1>For loop in Vue js</h1>
    <table>
      <tr>
        <td>ID</td>
        <td>Name</td>
        <td>Email</td>
      </tr>
      <tr v-for="user in users" :key="user.id">
        <td>{{ user.id }}</td>
        <td>{{ user.name }}</td>
        <td>{{ user.email }}</td>
      </tr>
    </table>
  </div>
</template>
