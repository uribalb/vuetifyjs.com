<template>
  <v-timeline>
    <v-timeline-item
      v-for="n in 4"
      :key="n"
    >
      <v-card>
        <v-card-text>
          Hello this is text.
        </v-card-text>
      </v-card>
    </v-timeline-item>
  </v-timeline>
</template>
