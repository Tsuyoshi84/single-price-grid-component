<template>
  <div class="container">
    <div class="title">Why Us</div>
    <ul class="why-us-list">
      <li>Tutorials by industry experts</li>
      <li>Peer &#38; expert code review</li>
      <li>Coding exercises</li>
      <li>Access to our GitHub repos</li>
      <li>Community forum</li>
      <li>Flashcard decks</li>
      <li>New videos every week</li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'CardUs',
});
</script>

<style scoped>
.container {
  color: var(--color-inverted-font);
  background-color: var(--color-light-cyan);
  text-align: left;
  padding: var(--padding-block) var(--padding-inline);
  border-radius: 0 0 var(--border-radius) var(--border-radius);
}

.title {
  font-size: 18px;
  font-weight: 700;
}

.why-us-list {
  font-size: 14px;
  list-style-type: none;
  padding-inline-start: 0;
}
</style>
