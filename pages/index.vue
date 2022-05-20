<template>
  <div class="home">
    <Hero />
  </div>
</template>

<script>
import axios from '@nuxtjs/axios'
export default {
  data() {
    return {
      movies: [],
    }
  },
  methods: {
    async getMovies() {
      const data = axios.get()
    },
  },
}
</script>
