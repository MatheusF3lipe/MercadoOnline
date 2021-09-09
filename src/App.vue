<template>
  <v-app>
    <v-toolbar class="red white--text">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-row no-gutters>
        <v-col class="pa-2 mt-3">
          <v-toolbar-title>Supermercado Online</v-toolbar-title>
        </v-col>
     
        <v-spacer></v-spacer>
        <v-col class="pa-2 mt-2 white--text">
          <v-text-field
            v-model="search"
            append-icon="mdi-magnify"
            label="Pesquisar Produto"
            single-line
            hide-details
           
          ></v-text-field>
        </v-col>
         <v-spacer></v-spacer>
     
        <v-col class="pa-2 mt-2">
          <v-btn icon>
            <v-icon class="white--text">mdi-account</v-icon>
          </v-btn>
          <v-btn icon>
            <v-icon class="white--text">mdi-heart</v-icon>
          </v-btn>
          <v-btn icon>
            <v-icon class="white--text">mdi-cart</v-icon>
          </v-btn>
        </v-col>
      </v-row>
   
    </v-toolbar>

    <v-main>
      <v-container>
        <v-row>
          <v-col v-for="n in 12" :key="n" cols="4">
            <v-card height="200"></v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
<style></style>

<script>
export default {
  //
};
</script>
