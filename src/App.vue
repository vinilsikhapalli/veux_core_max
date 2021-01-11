<template>
  <div id="app">
    <!-- <app-result :count="count"></app-result>
      <app-counter @updateCounter ="count+= $event" ></app-counter> -->
      <app-result></app-result>
      <app-counter></app-counter>
  </div>
</template>

<script>
import AppCounter from "./components/Count.vue";
import AppResult from "./components/Result.vue";
export default {
  name: 'App',
  components: {
    AppCounter,
    AppResult
  },
  
}
</script>

<style>

</style>
