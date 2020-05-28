<template>
  <div class="home">
    <TestComponent/>
  </div>
</template>

<script>
import TestComponent from '@/components/TestComponent.vue';

export default {
  name: 'Home',
  components: {
    TestComponent,
  },
};
</script>
