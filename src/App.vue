<script>
import AppTitle from './components/AppTitle.vue'

export default {
  components: {
    AppTitle
  },
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
  <!-- with option object in the same app -->
  <h1>{{ message }}</h1>

  <!-- with option object in the other app -->
  <AppTitle />
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
