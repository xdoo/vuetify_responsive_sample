<template>
  <v-app>
    <v-app-bar
      app
      color="black"
      dark
    >
      <span class="headline">Responsive</span><span class="font-weight-light headline">Sample</span>

      <v-spacer></v-spacer>

      <v-icon title="blubbber...">mdi-flask-outline</v-icon>
    </v-app-bar>

    <v-content>
      <v-container>
        <v-row class="pa-3">
          <h1 class="text-display-2 text-md-title">
            This is my Heading
          </h1>
        </v-row>
        <v-row class="pa-3">
          <p class="text--secondary"> 
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet,
          </p>
        </v-row>
      <Form></Form>
      </v-container>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component } from "vue-property-decorator"
import Form from './components/Form.vue'

@Component({
  components: {
    Form
  }
})
export default class App extends Vue {
}
</script>
