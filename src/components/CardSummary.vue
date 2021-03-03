<template>
  <div class="container">
    <h1 class="header">Join our community</h1>
    <p class="detail">30-day, hassle-free money back guarantee</p>
    <p class="sub-detail">
      Gain access to our full library of tutorials along with expert code reviews.<br />
      Perfect for any developers who are serious about honing their skills.
    </p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'CardSummary',
});
</script>

<style scoped>
.container {
  text-align: left;
  padding: var(--padding-block) var(--padding-inline);
}

.header {
  color: var(--color-cyan);
  font-size: 24px;
}

.detail {
  color: var(--color-bright-yellow);
  font-size: 20px;
  font-weight: 700;
}

.sub-detail {
  color: var(--color-grayish-blue);
}
</style>
