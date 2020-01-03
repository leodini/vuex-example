<template>
  <div id="app">
    <LinkList/>
  </div>
</template>

<script>
import LinkList from './components/LinkList.vue'

export default {
  name: 'app',
  components: {
    LinkList
  }
}
</script>

<style>
 #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
  }
</style>
