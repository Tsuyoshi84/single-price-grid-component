<template>
  <div class="container">
    <div class="title">Monthly Subscription</div>
    <div class="price-wrapper">
      <span class="price">$29</span>
      <span class="unit">per month</span>
    </div>
    <div class="info">Full access for less than $1 a day</div>
    <button class="sign-up-button">Sign Up</button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'CardPrice',
});
</script>

<style scoped>
.container {
  color: var(--color-inverted-font);
  text-align: left;
  background-color: var(--color-cyan);
  padding: var(--padding-block) var(--padding-inline);
  width: 100%;
}
.title {
  font-weight: 700;
  font-size: 17px;
  margin-block-end: 18px;
}
.price-wrapper {
  margin-block-end: 6px;
  display: flex;
  align-items: center;
}
.price {
  font-weight: 700;
  font-size: 30px;
}
.unit {
  font-size: 14px;
  margin-inline-start: 12px;
  display: inline-block;
}
.info {
  margin-block-end: 28px;
}
.sign-up-button {
  color: var(--color-inverted-font);
  font-size: 16px;
  font-weight: 700;
  background-color: var(--color-bright-yellow);
  border: none;
  border-radius: 4px;
  width: 100%;
  height: 50px;
  box-shadow: 4px 4px 5px 5px rgba(0, 0, 0, 0.1);
}

@media only screen and (min-width: 600px) {
  .container {
    border-radius: 0 0 0 var(--border-radius);
  }
}
</style>
