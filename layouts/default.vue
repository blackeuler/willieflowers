<template>
  <v-app light>
    <v-content>
      <Navbar />
      <v-container fluid class="secondary--text">
        <nuxt />
      </v-container>
    </v-content>

    <v-footer white--text color="secondary">
      <span class="primary--text">&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
import Navbar from '../components/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>
