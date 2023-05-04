<template>
  <div class="home">
    <h1>徐新环大傻逼李东娜大傻逼</h1>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  data () {
    return {
      iofo: '刘梦11'
    }
  },
  components: {
    HelloWorld
  }
}
</script>
