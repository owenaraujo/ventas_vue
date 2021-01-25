<template>
  <div id="app">
   
    <Nav></Nav>
    <Links/>
  </div>
</template>

<script>
import Nav from './components/nav.vue'
import Links from './components/links.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Links
  }
}
</script>
