<template>
  <div>
    <h1>Checking out Nuxt 3</h1>
    <p>{{ works }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      works: "works yay",
    };
  },
};
</script>

<style scoped>
h1 {
  margin: 0;
}
div {
  background-color: #05bd70;
}
</style>
