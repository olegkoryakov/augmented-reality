<template>
  <div
    class="aframe-wrapper"
  >
    <a-scene embedded arjs>
      <!-- <a-sphere
        position="0 1.25 -5"
        radius="1.24"
        color="red"
      /> -->
      <a-marker
        preset="hiro"
      >
        <a-box color="#ff0" scale="0.5 0.5 0.5" material="opacity: 0.5"></a-box>
      </a-marker>
      <a-entity camera>
        <a-cursor></a-cursor>
      </a-entity>
    </a-scene>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
