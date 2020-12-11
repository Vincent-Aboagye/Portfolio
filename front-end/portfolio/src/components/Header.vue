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
          Home
        </v-btn>

        <v-btn text>
          Contact
        </v-btn>

        <v-btn text>
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