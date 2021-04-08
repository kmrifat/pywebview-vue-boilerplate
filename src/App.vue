<template>
  <div>
    <h1>Hello World</h1>
    <input type="text">
    <input type="password">
    <input type="checkbox">
    <br>
    <button @click="myBtn">Hello</button>
  </div>
</template>

<script>
export default {
  name: "App",
  methods: {
    myBtn() {
      console.log(window.pywebview.api.takeScreenshot());
    }
  }
}
</script>

<style scoped>

</style>