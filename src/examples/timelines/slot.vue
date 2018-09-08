<template>
  <v-timeline>
    <v-timeline-item
      v-for="n in 4"
      :key="n"
    >
      <div slot="opposite">This is opposite text</div>
      <v-card>
        <v-card-text>
          Hello world.
        </v-card-text>
      </v-card>
    </v-timeline-item>
  </v-timeline>
</template>
