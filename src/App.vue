<template>
  <div>
    <nav-bar/>
    <hero/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'app',
  components: {
    NavBar,
    Hero
  },
}
</script>

