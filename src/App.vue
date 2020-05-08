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
      <responsive-font></responsive-font>
      <Form></Form>
      </v-container>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component } from "vue-property-decorator"
import Form from '@/components/Form.vue'
import ResponsiveFont from "@/components/ResponsiveFont.vue"

@Component({
  components: {
    Form,
    ResponsiveFont
  }
})
export default class App extends Vue {
}
</script>
