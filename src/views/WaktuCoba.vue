<template>
  <div>
    <h2>Hallo</h2>
    <Timer />
    <hr />
    <div>
      <stop-watch />
    </div>
  </div>
</template>

<script>
import StopWatch from "../components/StopWatch.vue";
import Timer from "../components/Timer.vue";
export default {
  name: "WaktuCoba",
  components: {
    Timer,
    StopWatch,
  },
};
</script>

<style></style>
