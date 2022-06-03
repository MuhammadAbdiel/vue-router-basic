<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloVue msg="Welcome to Vue.js!" />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloVue from '../components/HelloVue.vue'
import HelloVue from '@/components/HelloVue.vue'

export default {
  name: 'HomeView',
  components: {
    HelloVue
  }
}
</script>
