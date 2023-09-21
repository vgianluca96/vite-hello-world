<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  data() {
    return {
      message: 'Hello Vite'
    }
  },
  components: {
    AppTitle,
    AppHero
  }
}

</script>

<template>
  <h1>
    {{ message }}
  </h1>

  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>

<style></style>
