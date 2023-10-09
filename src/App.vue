<template>
  <p v-text="name"></p>
  <div>{{ name }}</div>

  <div v-html="pop"></div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      name: "inno",
      pop: `<a href="#" onclick="alert('hello')">greet</a>`,
  };
},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
