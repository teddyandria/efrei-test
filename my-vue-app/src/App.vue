<template>
  <MyNavbar />
  <HomePage msg="Hello" />
</template>

<script>
import HomePage from './components/HomePage.vue';
import MyNavbar from './components/MyNavbar.vue';


export default {
  name: 'App',
  components: {
    HomePage,
    MyNavbar
  },
  // props: {
  //   msg: String
  // }
}
</script>

<style></style>
