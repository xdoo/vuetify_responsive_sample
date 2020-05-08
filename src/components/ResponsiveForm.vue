<template>
  <v-container>
    <v-row>
      <v-col cols="12" md="6" lg="6" xl="6">
        <v-text-field
            label="Field R1C1"
          ></v-text-field>
      </v-col>
      <v-col cols="12" sm="6" md="3" lg="3" xl="3">
        <v-text-field
            label="Field R1C2"
          ></v-text-field>
      </v-col>
      <v-col cols="12" sm="6" md="3" lg="3" xl="3">
        <v-text-field
            label="Field R1C3"
          ></v-text-field>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" md="6" lg="6" xl="6">
        <v-text-field
            label="Field R2C1"
          ></v-text-field>
      </v-col>
      <v-col cols="12" md="6" lg="6" xl="6">
        <v-text-field
            label="Field R2C2"
          ></v-text-field>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" md="6" lg="6" xl="6">
        <v-text-field
            label="Field R3C1"
          ></v-text-field>
      </v-col>
      <v-col cols="12" md="6" lg="6" xl="6">
        <v-text-field
            label="Field R3C2"
          ></v-text-field>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12">
        <v-text-field
            label="Field R4C1"
          ></v-text-field>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="8" md="8" lg="10" xl="10">
        <v-text-field
            label="Field R5C1"
          ></v-text-field>
      </v-col>
      <v-col cols="12" sm="4" md="4" lg="2" xl="2">
        <v-text-field
            label="Field R5C2"
          ></v-text-field>
      </v-col>
    </v-row>
    <v-row>
      <v-btn>
        GO!
      </v-btn>
    </v-row>
  </v-container>  
</template>
<script lang="ts">
import Vue from 'vue'
import { Component } from "vue-property-decorator"

@Component
export default class ResponsiveForm extends Vue{
  
}
</script>