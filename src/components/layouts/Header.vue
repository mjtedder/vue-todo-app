<template>
  <header class="header">
    <img alt="Vue logo" src="../../assets/logo.png" />
    <h1>Vue.js Todo List</h1>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
img {
    size: 100px;
}
.header {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}
.header a {
  color: #fff;
  padding-right: 5px;
}
</style>