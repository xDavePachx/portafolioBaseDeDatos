<template>
  <div class="home">
    <center><img alt="Targarien logo" width="500" src="https://dosideas.com/images/stories/bases-de-datos/cover/der-base-de-datos-en-perspectiva.jpg">
    </center>
    <br>
    <br>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
