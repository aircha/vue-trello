<template>
  <div>
    Home Page
    <div>
      Board List:
      <ul>
        <li>
          <router-link to="/b/1">Board 1</router-link>
        </li>
      </ul>
      <ul>
        <li>
          <router-link to="/b/2">Board 2</router-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Home"
  }
</script>

<style scoped>

</style>
