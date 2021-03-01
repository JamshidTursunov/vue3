<template>
  <div class="container about">
    <div class="row">
      <div class="col-md-12">
        <h1>This is about page</h1>
      </div>
    </div>
    <counter class="col-md-4" />
  </div>
</template>

<script>
import counter from "../components/counter";

export default {
  components: {
    counter
  },
  data() {
    return {
      x: null
    };
  }
};
</script>
