<style scoped>
  @import "./style.css";
</style>
<template>
  <div id="contents">
    <div id="particles-js"></div>
  </div>
</template>
<style  scoped>
</style>
<script>
  import "particles.js";
  import particlesConfig from "./particles.json";
  export default {
    data() {
      return {};
    },
    mounted() {
      this.init();
    },
    methods: {
        init(config = particlesConfig) {
            // eslint-disable-next-line no-undef
            particlesJS('particles-js', config);
        },
    }
  };
</script>
