<template>
  <div id="app">
    <Navbar />
    <Sites />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Sites from "./components/Sites.vue";
export default {
  name: "app",
  data() {
    return {
      title: "Electrified Shopping"
    };
  },
  components: {
    Navbar,
    Sites
  }
};
</script>

