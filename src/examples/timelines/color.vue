<template>
  <v-timeline>
    <v-timeline-item
      v-for="n in 4"
      :key="n"
      color="orange"
    >
      <v-card>
        <v-card-text>
          Hello world.
        </v-card-text>
      </v-card>
    </v-timeline-item>
  </v-timeline>
</template>
