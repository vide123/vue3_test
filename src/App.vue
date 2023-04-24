<template>
  <h1>{{ name }}</h1>
  <h2>{{ age }}</h2>
  <button @click="changeInfo">我是谁！！！！！测试    </button>
</template>

<script>

import {ref} from 'vue'
  export default {
    name: 'App',
   setup(){
    let name =ref('张ss')
    let age = ref(18)
    let job = ref({
    })
   function changeInfo(){
     name.value = "李四"
     age.value = 48
   }

    return {
      name,
      age,
      changeInfo
    }
   }
  }
</script>
