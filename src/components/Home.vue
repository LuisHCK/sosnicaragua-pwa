<template>
  <div class="page-home page-container">
    <app-header header="Inicio"></app-header>
  </div>
</template>

<script>
import Header from './layout/Header.vue'

export default {
  components: {
    'app-header': Header
  },

  data() {
    return {
      posts: []
    }
  }
}
</script>

<style>

</style>
