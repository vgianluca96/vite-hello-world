<script>
import AppTitle from './components/AppTitle.vue'

export default {
  data() {
    return {
      message: 'Hello Vite'
    }
  },
  components: {
    AppTitle
  }
}

</script>

<template>
  <h1>
    {{ message }}
  </h1>

  <AppTitle></AppTitle>
</template>

<style></style>
