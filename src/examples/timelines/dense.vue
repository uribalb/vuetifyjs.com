<template>
  <v-timeline dense>
    <v-timeline-item
      v-for="n in 4"
      :key="n"
    >
      <v-card>
        <v-card-text>
          Hello world.
        </v-card-text>
      </v-card>
    </v-timeline-item>
  </v-timeline>
</template>
