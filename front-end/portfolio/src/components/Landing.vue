<template>
  <div class="hello">
    <v-app id="inspire">
      <Header />
    <v-main>
    <v-container fluid style="height: 1500px;"></v-container>
    </v-main>
    </v-app>
  </div>
  
</template>

<script>
import Header from './Header'
export default {
  name: 'Landing',
  components: {
    Header
  },
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
