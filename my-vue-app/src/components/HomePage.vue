<template>
  <h1 class="headTitle">{{ msg }}</h1>
</template>

<script>
//import MyNavbar from './MyNavbar.vue'


export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.headTitle {
  text-align: center;
}
</style>
