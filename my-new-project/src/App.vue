<template>
  <div id="app">
    <CodeCommits/>
    <PerformanceMetrics/>
    <ErrorRate/>
  </div>
</template>

<script>
import CodeCommits from './components/CodeCommits.vue';
import PerformanceMetrics from './components/PerformanceMetrics.vue';
import ErrorRate from './components/ErrorRate.vue';

export default {
  name: 'App',
  components: {
    CodeCommits,
    PerformanceMetrics,
    ErrorRate
  }
}
</script>

<style>
#app {
  text-align: center;
  margin-top: 50px;
}
</style>
