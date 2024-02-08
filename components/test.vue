<template>
  <div class="main">
    <h1>Nuxt JS</h1>
    <p>Layout and Nuxt component</p>
    <!-- <label>
      Input field
      <input class="input" v-model="testData">
    </label>
    <p class="result">{{ testData }}</p> -->
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
.main {
  padding: 50px 90px;
  background: rgba(255,255,255, 0.8);
  border-radius: 4px;
  text-align: left;
}
.input {
  width: 100px;
  height: 30px;
  border: 1px solid red;
}

.result {
  color: green;
}
</style>
