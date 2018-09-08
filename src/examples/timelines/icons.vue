<template>
  <v-timeline>
    <v-timeline-item
      v-for="n in 4"
      :key="n"
      icon="location_on"
      small
    >
      <v-card>
        <v-card-text>
          Hello world.
        </v-card-text>
      </v-card>
    </v-timeline-item>
  </v-timeline>
</template>
