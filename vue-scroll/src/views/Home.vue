<template>
  <div class="home">
    <div class="section">
      Section1
    </div>
    <div class="section">
      Section2
    </div>
    <div class="section">
      Section3
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
<style>
.home>div:nth-child(1){
  background: gray;
}
.home>div:nth-child(2){
  background: yellow;
}
.home>div:nth-child(3){
  background: green;
}
  .section{
    width: 100vw;
    height: 100vh;
  }
</style>
