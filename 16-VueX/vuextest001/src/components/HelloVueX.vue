<template>
  <div>
    <h2>Hello VueX</h2>
    <h2>{{$store.state.counter}}</h2>
    <h2>{{$store.getters.more20stu}}</h2>
    <h2>{{$store.getters.more20stuLength}}</h2>
    <h2>{{$store.getters.moreAgeStu(12)}}</h2>
  </div>
</template>

<script>
  export default {
    name: "HelloVueX",
  }
</script>

<style scoped>

</style>
