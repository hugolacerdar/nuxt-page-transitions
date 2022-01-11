<template>
  <main>
    <h1>First Page</h1>
    <ul>
      <li><nuxt-link exact to="/second-page">Go to Second Page</nuxt-link></li>
    </ul>
  </main>
</template>

<script>
export default {
  name: "IndexPage",
  transition: "fadeOpacity",
};
</script>

<style scoped>
main {
  background-color: #333;
  color: white;
  height: 100vh;
  padding: 100px;
}
li > a {
  color: white;
}

.fadeOpacity-enter-active,
.fadeOpacity-leave-active {
  transition: background-color 0.35s ease-out;
}

.fadeOpacity-enter-from,
.fadeOpacity-leave-to {
  background-color: rgb(87, 37, 37);
}
</style>

