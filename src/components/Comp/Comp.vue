<template>
  <div class="flex h-full w-full justify-center items-center bg-yellow-light">
    <div class="justify-center items-center text-5xl relative">
      <WindmillMatrix></WindmillMatrix>
    </div>
  </div>
</template>

<script>
import WindmillMatrix from "../WindmillMatrix/WindmillMatrix.vue";
export default {
  name: "Comp",
  props:['text'],
  data(){
    return{
    }
  },
  components:{
    WindmillMatrix,
  },
  computed:{
  }
}
</script>
<style lang="less" scoped>
@import "res/style/comp.less";
.text_shadow{
  opacity: 0.2;
}
</style>