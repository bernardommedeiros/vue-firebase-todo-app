<script setup>
import Header from './components/Header.vue'
import Input from "./components/Input.vue";
</script>

<template>
  <div class="main">
    <div  class="box mt-4">
      <Header/>

      <Input  />
    </div>

  </div>

</template>

<style scoped>

.main {
  max-width: 600px;
  padding: 20px;
  margin: 0 auto;
}

</style>
