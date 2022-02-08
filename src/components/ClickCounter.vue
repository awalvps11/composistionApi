<template>
  <button @click="incrementCount">Clicked {{ count }} Times</button>
</template>

<script>
export default {
  name: "ClickCount",
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
