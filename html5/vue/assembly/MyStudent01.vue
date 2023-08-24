<template>
  <div>
    <h1>学生:{{name}}</h1>
    <h1>年龄:{{age}}</h1>
  </div>
</template>

<script>
export default {
  name: "MyStudent01",
  data:function (){
    return {
      name:'zola',
      age:19
    }
  }
}
</script>

<style scoped>

</style>