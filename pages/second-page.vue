<template>
  <main>
    <h1>Second Page</h1>
    <ul>
      <li><nuxt-link exact to="/">Go to Index Page</nuxt-link></li>
    </ul>
  </main>
</template>

<script>
export default {
  name: "SecondPage",
};
</script>

<style scoped>
main {
  background-color: rgb(87, 37, 37);
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
  background-color: #333;
}
</style>