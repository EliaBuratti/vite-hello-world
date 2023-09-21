<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero
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
  <AppHero />

  <!-- with option object in the same app -->
  <h1>{{ message }}</h1>

  <!-- with option object in the other app -->
  <AppTitle />
</template>

<style scoped></style>
