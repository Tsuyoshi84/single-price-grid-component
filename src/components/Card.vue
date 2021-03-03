<template>
  <section class="card-container">
    <card-summary />
    <card-price />
    <card-us />
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import CardSummary from './CardSummary.vue';
import CardPrice from './CardPrice.vue';
import CardUs from './CardUs.vue';

export default defineComponent({
  name: 'Card',
  components: { CardSummary, CardPrice, CardUs },
});
</script>

<style scoped>
.card-container {
  width: 100%;
  max-width: 634px;
  box-shadow: 0 0 12px 12px rgba(0, 0, 0, 0.05);
  border-radius: var(--border-radius);
}
</style>
