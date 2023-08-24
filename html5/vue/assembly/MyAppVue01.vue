<template>
<div>
  <MyVue01></MyVue01>
  <MyStudent01></MyStudent01>
</div>
</template>

<script>
import MyVue01 from "./MyVue01.vue";
import MyStudent01 from "./MyStudent01.vue";
export default {
  name: "MyAppVue01",
  components:{
    MyVue01,
    MyStudent01
  }
}
</script>

<style scoped>

</style>