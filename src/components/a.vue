<template>
  <div id="app">
    <s>{{$name}}</s>
  </div>
</template>

<script>
import s from '@/components/HelloWorld.vue'

export default {
  data(){
    return {
      name:'zs'
    }
  },
  components:{
    s
  }
  
}
</script>

<style lang="less">

</style>