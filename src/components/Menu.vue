<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Icon name="camera" :size="50" color="red" />
  </div>
</template>

<script>
import Icon from './Icon/Icon.vue';
export default {
  name: 'Menu',
  props: {
    msg: String,
  },
  components: {
    Icon,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
