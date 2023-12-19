<template>
  <div>
    <h1>Hello World!</h1>
    <label>
      Input field
      <input class="input" v-model="testData">
    </label>
    <p class="result">{{ testData }}</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        testData: ''
      }
    }
  }
</script>

<style scoped>
.input {
  width: 100px;
  height: 30px;
  border: 1px solid red;
}

.result {
  color: green;
}
</style>
