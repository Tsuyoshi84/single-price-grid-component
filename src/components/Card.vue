<template>
  <section>
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

<style scoped></style>
