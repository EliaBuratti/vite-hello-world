<script>
export default {
  // questo é il vs options object
  data() {
    return {
      message: 'Hello Vite',
    }
  },
  methods: {
  }
}
</script>

<template>
  <h1>{{ message }}</h1>
</template>









<!-- <script setup>
import HelloWorld from './components/HelloWorld.vue'
</script> -->

<!-- <template>
  <div>
    <h1>hello vue</h1>
  </div>
    <HelloWorld msg="Vite + Vue" />

</template> -->

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
