<template>
  <HelloWorld msg="Hello World!"/>
  <h1 class="center">This is a {{ txt }} :)</h1>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data() {
    return {
      txt: "Vue Example"
    }
  },
  components:{
    HelloWorld
  }
}
</script>

<style scoped>
  .center {
    text-align: center;
  }
</style>
