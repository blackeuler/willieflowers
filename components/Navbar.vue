<template>
  <nav>
    <v-toolbar dense color="secondary" class="">
      <v-toolbar-side-icon flat color="primary" @click="drawer = !drawer" />
      <v-spacer />
      <v-toolbar-items color="primary" class="hidden-sm-and-down primary--text">
        <v-btn color="primary" flat>
          Bio
        </v-btn>
        <v-btn color="primary" flat>
          Issues
        </v-btn>
        <v-btn color="primary" flat>
          Blog
        </v-btn>
        <v-btn color="primary" flat>
          Donate
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <v-navigation-drawer v-model="drawer" app class="secondary">
      <v-list dense nav>
        <v-list-item>
          <v-list-item-content>
            <v-btn color="primary" flat to="/" nuxt>
              <v-icon>home</v-icon>
              <v-list-item-title>Home</v-list-item-title>
            </v-btn>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <v-btn color="primary" flat to="/" nuxt>
              <v-icon>home</v-icon>
              <v-list-item-title>Home</v-list-item-title>
            </v-btn>
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <v-btn color="primary" flat to="/" nuxt>
              <v-icon>home</v-icon>
              <v-list-item-title>Home</v-list-item-title>
            </v-btn>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      drawer: false
    }
  }
}
</script>

<style></style>
