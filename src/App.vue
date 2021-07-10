<template>
  <div id="app">
    <h1> ToDoアプリ</h1>
      <input type="text" v-model="textInput">
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
