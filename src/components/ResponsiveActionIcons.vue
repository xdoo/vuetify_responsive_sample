<template>
<div>
  <div v-if="shrink">
    <v-btn
      icon
      @click="show()"
    >
      <v-icon title="open">mdi-menu</v-icon>
    </v-btn>
  </div>
  <div v-else>
    <v-btn icon>
      <v-icon title="rooooar...">mdi-gauge-full</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon title="pfiiiit...">mdi-whistle</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon title="kawooom...">mdi-weather-lightning</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon title="wuuuusch...">mdi-auto-fix</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon title="brizzel...">mdi-atom</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon title="blubbber...">mdi-flask-outline</v-icon>
    </v-btn>
  </div>
</div>
</template>
<script lang="ts">
import Vue from 'vue'
import { Component } from "vue-property-decorator"

@Component
export default class ResponsiveActionIcons extends Vue {

  get shrink() {
    return this.$vuetify.breakpoint.smAndDown
  }

  show() {
    console.log("show menu...")
  }

}
</script>