<template>
  <v-layout justify-center>
    <v-flex
      xs12
      sm10
      md8
      lg6
    >
      <a
        class="d-block"
        href="#!"
        style="text-decoration: none;"
        @click.prevent=""
      >
        <v-paper
          elevation="12"
        >
          <v-img
            aspect-ratio="1.5"
            class="text-xs-right"
            position="top"
            src="https://cdn.vuetifyjs.com/images/store/navy-grid-shirt.png"
          >
            <v-avatar
              class="display-1 ma-3"
              color="red lighten-3"
              dark
              size="72"
            >
              <span class="subheading font-weight-black">$</span>
              23
            </v-avatar>
          </v-img>
          <v-paper
            class="py-3 px-4 title font-weight-light text-xs-center"
            color="indigo darken-1"
            dark
          >
            Buy Now
          </v-paper>
        </v-paper>
      </a>
    </v-flex>
  </v-layout>
</template>
