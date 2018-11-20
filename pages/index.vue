<template>
  <v-app>
    <v-toolbar
      app
      flat
      dark
      color="primary"
    >
      <v-toolbar-title>
        <h1>Presentations</h1>
      </v-toolbar-title>
    </v-toolbar>

    <v-content>
      <v-container>
        Container
      </v-container>
    </v-content>

    <v-footer
      app
      class="pa-3"
    >
      <p class="ma-0">© {{ author }}</p>
    </v-footer>
  </v-app>
</template>

<script>
import { author } from '../package'

export default {
  name: 'Home',

  data() {
    return {
      author
    }
  }
}
</script>
