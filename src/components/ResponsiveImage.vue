<template>
  <v-container class="ma-0 pa-0" fluid>
    <v-row>
      <v-img 
        src="http://catify.de/web/pics/responsive_sample/village_1264.jpg"
        lazy-src="http://catify.de/web/pics/responsive_sample/village_blur.jpg"
        srcset="http://catify.de/web/pics/responsive_sample/village_600.jpg 600w,
                http://catify.de/web/pics/responsive_sample/village_960.jpg 960w,
                http://catify.de/web/pics/responsive_sample/village_1264.jpg 1264w,
                http://catify.de/web/pics/responsive_sample/village_1904.jpg 1904w,
                http://catify.de/web/pics/responsive_sample/village_2400.jpg 2400w"
        width="100%"
      >
      </v-img>
    </v-row>
    <v-row justify="center">
      <span class="mt-2 mb-10 text-caption text--secondary">Nice village in South-Tirol</span>
    </v-row>
  </v-container>
</template>
<script lang="ts">
import Vue from 'vue'
import { Component } from "vue-property-decorator"

@Component
export default class ResponsiveImage extends Vue{
    
}
</script>