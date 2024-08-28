<template>
  <h1>Vue JS</h1>
  <button @click="click">Кнопочка</button>

</template>


<script setup>
  import { onMounted, ref } from 'vue'
  // import Header from './components/Header.vue'
  // import Counter from './components/Counter.vue'

  const counter = ref(0)
  const message = ref('')
  const checked = ref('true')
  
  function inc () {
    counter.value++
  }

  function click() { 
    seen.value = !seen.value 
  }

  onMounted(() => {
    console.log(counter)
  })
</script>

<style>
#app {
  width: 900px;
  margin: auto;
}
</style>