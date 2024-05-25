<template>
  <div>
    <h1>Error Rate: {{ errorRate }}%</h1>
  </div>
</template>

<script>
export default {
  name: 'ErrorRate',
  data() {
    return {
      errorRate: 'Loading...'
    };
  },
  mounted() {
    this.fetchErrorRate();
  },
  methods: {
    fetchErrorRate() {
      // Placeholder for API call
      this.errorRate = 0.5; // Simulated error rate
    }
  }
}
</script>
