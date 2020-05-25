<template>
  <div>
    <header>
      <h1>Veather App</h1>
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped>
header {
  background: #333;
  padding: 0.2rem;
  text-align: center;
  color: #fff;
  text-align: center;
}
</style>
