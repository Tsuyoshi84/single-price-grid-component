<template>
  <section class="card-container">
    <card-summary />
    <div class="small-parts-container">
      <card-price />
      <card-us />
    </div>
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
  max-width: 310px;
  box-shadow: 0 0 12px 12px rgba(0, 0, 0, 0.05);
  border-radius: var(--border-radius);
  margin: 0 16px;
}

.small-parts-container {
  display: flex;
  flex-direction: column;
}

@media only screen and (min-width: 600px) {
  .card-container {
    max-width: 634px;
  }
  .small-parts-container {
    flex-direction: row;
  }
}
</style>
