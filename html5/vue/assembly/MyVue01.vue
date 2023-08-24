<template>
<!--  vue用例写HTML的-->
  <div class="demo">
    <h1>学校:{{schoolName}}</h1>
    <h1>地址:{{address}}</h1>
    <button @click="showName">点我提示学校名字</button>
  </div>
</template>
<script>
//vue 用例写脚本的
export default {
  name:"MyVue01",
  data:function(){
    return {
      schoolName:'新江中心小学',
      address:"nn"
    }
  },
  methods:{
    showName(){
      alert(this.schoolName)
    }
  }
}
// export default school
</script>

<style scoped>
/*
vue 用来写css的

*/
.demo{
  background-color: #ff9500;
}
</style>