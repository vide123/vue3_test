<template>
  <h1>{{ name }}</h1>
  <h2>{{ age }}</h2>
  <button @click="sayname">我是谁！！！！！测试</button>
  <h1>使用了dev分支</h1>
</template>

<script>
  export default {
    name: 'App',
   setup(){                                                                                              11111111111111111111111111111111111111111111111111111111111
    let name ='张三'
    let age = 18
    function sayname() {
      alert(`我${name},我${age}岁`)
    }

    return {
      name,
      age,
      sayname
    }
   }
  }
</script>
