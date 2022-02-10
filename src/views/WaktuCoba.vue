<template>
  <div>
    <h2>Hallo</h2>
    <Timer />
    <hr />
    <div>
      <stop-watch />
    </div>
    <hr />
    <div>
      <demo-one />
    </div>
    <hr />
    <div>
      <methode />
    </div>
  </div>
</template>

<script>
import DemoOne from "../components/DemoOne.vue";
import Methode from "../components/Methode.vue";
import StopWatch from "../components/StopWatch.vue";
import Timer from "../components/Timer.vue";
export default {
  name: "WaktuCoba",
  components: {
    Timer,
    StopWatch,
    DemoOne,
    Methode,
  },
};
</script>

<style></style>
