<template>
  <div>
    <h1>Полезные свойства капусты</h1>
    <p>Капуста давно и прочно вошла в рацион питания и принадлежит к числу важнейших овощных растений.
    Она является неотъемлемой частью таких традиционных блюд, как борщ, щи, солянка, тушеная капуста, голубцы, капустная запеканка и квашеная капуста.</p>
    <p>Капуста богата витаминами А, В1, Р, К, В6, U. Она является лидером среди овощей по содержанию витамина С, причём он сохраняется в капусте как при длительном хранении в сыром виде, так и при термической обработке.
    В капусте также много минералов — серы, кальция, калия и фосфора, клетчатки и воды.</p>
  </div>
  <button @click="click">Like</button>

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
template
  
#app {
  width: 900px;
  margin: auto;
}
</style>