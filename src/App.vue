<template>
  <div>
    <hello-world />
    <button class="button is-primary">This is a button</button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
}
</script>

