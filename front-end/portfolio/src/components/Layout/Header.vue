<template>
  <v-app-bar 
    app
    elevation=3
    color="#fff">
    <v-container>
      <v-toolbar flat>
        <v-toolbar-title>Portfolio</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items>
        <v-btn text>
          <v-icon >mdi-home-outline</v-icon>
          Home
        </v-btn>

        <v-btn text>
          <v-icon >mdi-contacts</v-icon>
         Contact 
        </v-btn>

        <v-btn text>
          <v-icon >mdi-information-variant</v-icon>
           About 
        </v-btn>
        </v-toolbar-items>
      </v-toolbar>
    </v-container>
  </v-app-bar>
</template>


<script>
  export default {
      name: 'Header',
  data() {
    return{
    drawer: false
    }
        
    }
      
  }
</script>

<style scoped>

</style>