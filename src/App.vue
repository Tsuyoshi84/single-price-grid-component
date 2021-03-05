<template>
  <main>
    <div class="card-wrapper">
      <Card />
    </div>
    <img src="./assets/desktop-design.jpg" alt="" />
  </main>
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
:root {
  --color-cyan: hsl(179, 62%, 43%);
  --color-light-cyan: hsl(179.5, 47.2%, 51.8%);
  --color-bright-yellow: hsl(71, 73%, 54%);
  --color-light-gray: hsl(204, 43%, 93%);
  --color-grayish-blue: hsl(218, 22%, 67%);
  --color-inverted-font: #fff;
  --padding-inline: 22px;
  --padding-block: 22px;
  --border-radius: 4px;
}

@media only screen and (min-width: 600px) {
  :root {
    --padding-inline: 38px;
    --padding-block: 27px;
    --border-radius: 8px;
  }
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

#app {
  font-family: 'Karla', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.card-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
