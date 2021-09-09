<template>
  <v-app>

  <v-toolbar class="red white--text">
    
     <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Supermercado Online</v-toolbar-title>

      <v-spacer></v-spacer>

     <v-btn icon>
            <v-icon class="white--text">mdi-magnify</v-icon>     
      </v-btn>

      <v-btn icon>
          <v-icon class="white--text">mdi-account</v-icon>
        </v-btn>
     

      <v-btn icon>
        <v-icon class="white--text">mdi-heart</v-icon>
      </v-btn>
         <v-btn icon>
          <v-icon class="white--text">mdi-cart</v-icon>
        </v-btn>
  </v-toolbar>
    

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
<style></style>

<script>

export default {
  //
};
</script>
