<template>
  <h2 @mouseover="incrementCount">Clicked {{ count }} Times</h2>
</template>

<script>
export default {
  name: "HoverCount",
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    incrementCount() {
      this.count += 1;
    },
  },
};
</script>

<style></style>
