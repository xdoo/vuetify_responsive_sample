<template>
  <v-app>
    <v-app-bar
      app
      color="black"
      dark
    >
      <h1 class="headline">Responsive</h1><h1 class="font-weight-light headline text-truncate">Sample</h1>

      <v-spacer></v-spacer>
      <responsive-action-icons></responsive-action-icons>
    </v-app-bar>

    <v-content>
      <v-container>
        <responsive-font></responsive-font>
        <responsive-form></responsive-form>
      </v-container>
      <responsive-image></responsive-image>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component } from "vue-property-decorator"

// components
import ResponsiveForm from '@/components/ResponsiveForm.vue'
import ResponsiveFont from "@/components/ResponsiveFont.vue"
import ResponsiveActionIcons from "@/components/ResponsiveActionIcons.vue"
import ResponsiveImage from "@/components/ResponsiveImage.vue"

@Component({
  components: {
    ResponsiveForm,
    ResponsiveFont,
    ResponsiveActionIcons,
    ResponsiveImage
  }
})
export default class App extends Vue {
}
</script>
