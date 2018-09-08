<template>
  <v-timeline dense>
    <v-timeline-item
      v-for="n in 4"
      :key="n"
    >
      <v-alert :value="true" color="warning">
        Hello world.
      </v-alert>
    </v-timeline-item>
  </v-timeline>
</template>
