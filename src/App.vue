<template>
  <Card />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Card from './components/Card.vue';

export default defineComponent({
  name: 'App',
  components: {
    Card,
  },
});
</script>

<style>
#app {
  font-family: 'Karla', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
