<template>
  <div class="counter">
    <button>+</button>
    {{ counter }}
    <button>-</button>
    <h1>Counter value: {{ counter }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0,
      x: null,
    };
  },
};
</script>

<style scoped>
.counter {
  padding: 1rem 1rem;
  border: 1px solid red;
}
</style>
