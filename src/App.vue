<template>
  <v-app id="inspire">
    <v-app-bar app shrink-on-scroll class="red white--text">
      <v-toolbar-title
        >Supermercado Online

        <v-btn icon>
          <v-icon class="white--text">mdi-account</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon class="white--text">mdi-heart</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon class="white--text">mdi-cart</v-icon>
        </v-btn>
      </v-toolbar-title>
    </v-app-bar>

    <v-main>
      <v-container>
        <v-row>
          <v-col v-for="n in 24" :key="n" cols="4">
            <v-card height="200"></v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  //
};
</script>
