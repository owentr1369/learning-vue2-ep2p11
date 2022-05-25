<template>
  <div>
    <h1>Hello</h1>
    <input type="text" v-model="name" />
    <p>{{ name }}</p>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      name: "Tam",
    };
  },
  methods: {},
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
