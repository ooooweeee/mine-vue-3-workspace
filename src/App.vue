<template>
  <div class="app">This is {{ msg }}</div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  setup() {
    return {
      msg: 'Hello'
    };
  }
});
</script>
