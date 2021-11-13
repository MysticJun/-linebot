<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HELLO msg="歡迎光臨"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HELLO from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HELLO
  }
}
</script>
