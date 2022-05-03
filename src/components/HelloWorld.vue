<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Menu msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import Menu from './Menu.vue';

export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  components: {
    Menu,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
