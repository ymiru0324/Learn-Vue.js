<template>
  <div class="about">
    <h1>This is an about page</h1>
    <TestCoder>
      <template #header="{ test }"> <!-- # = v-slot: -->
        <p>header11 {{ test }}</p>
      </template>
      <template #default>
        hello1
      </template>
    </TestCoder>
  </div>
</template>

<script>
import TestCoder from '@/components/TestCoder.vue'

export default {
  components: {
    TestCoder
  }
}
</script>
