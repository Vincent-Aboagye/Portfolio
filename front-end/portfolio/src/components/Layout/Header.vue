<template>
<div>
  <v-app-bar 
    app
    color="#fff">
    <v-row>
    <v-container>
      <v-toolbar flat>
        <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer = true"></v-app-bar-nav-icon>
        <v-toolbar-title>Portfolio</v-toolbar-title>

        <v-toolbar-items class="hidden-sm-and-down text-center" >
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
  <v-navigation-drawer
      v-model="drawer"
      absolute
      temporary

    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="gray--text text--accent-4"
        >
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-home-outline</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-contacts</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Contact</v-list-item-title>
          </v-list-item>
          <v-list-item>

            <v-list-item-icon>
              <v-icon>mdi-information-variant</v-icon>
            </v-list-item-icon>
            <v-list-item-title>About</v-list-item-title>
          </v-list-item>

        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
</div>
  
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