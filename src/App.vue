<template>
  <div id="app">
    <h1> ToDoアプリ</h1>
      <input type="text" v-model="textInput">
      <p>{{ textInput }}</p>
  </div>
</template>

<script>

export default {
  data() {
    return {
      textInput: '',
    }
  }
}
</script>

<style>

</style>
