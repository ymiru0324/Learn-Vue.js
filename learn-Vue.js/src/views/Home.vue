<template>
  <div>
    <h1>This is Home page</h1>
    <TestCoder />
  </div>
</template>

<script>
import TestCoder from '@/components/TestCoder.vue';

export default {
  components: {
    TestCoder
  },
  data() {
    return {
      name: 'Test Coder'
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>