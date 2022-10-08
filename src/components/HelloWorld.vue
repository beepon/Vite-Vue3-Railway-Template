<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>

    <div id="app">
      {{ greeting }}
    </div>
    <script type="module" src="/src/main.js"></script>\
    <script>
       let App = Vue.createApp({
           data: function(){
            return {
             greeting: 'Hello Vue' 
            }
           }  
       })
       App.mount('#app');
    </script>

</template>

<style scoped>
a {
  color: #42b983;
}
</style>
