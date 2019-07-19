<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <h1>Vue SPC src Test</h1>
    <SrcT />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SrcT from '@/components/SrcT/SrcT.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    SrcT
  }
}
</script>
