<template>
  <div id="card">
    <the-result></the-result>
    <the-summary></the-summary>
  </div>
</template>

<script setup>
import TheResult from '/src/components/TheResult.vue';
import TheSummary from '/src/components/TheSummary.vue';
</script>

<style>
div#card {
  display: grid;
  grid-template-columns: 1fr 1fr;
  height: 23rem;
  width: 35rem;
  margin: 10% auto;
  border-radius: 25px 25px;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  background-color: hsl(0, 0%, 100%);
}

@media (min-width: 320px) and (max-width: 767px) {
  div#card {
    display: flex;
    flex-direction: column;
    width: 100vw;
    height: 100vw;
    margin: auto;
    box-shadow: none;
  }
}
</style>
