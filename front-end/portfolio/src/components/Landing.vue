<template>
  <div class="hello">
    <v-app id="inspire">
      <Header />
    <v-main>
      <Content />
    <!-- <v-container fluid style="height: 1500px;">
      
    </v-container> -->
    </v-main>
    <Footer />
    </v-app>
  </div>
  
</template>

<script>
import Header from './Layout/Header'
import Footer from './Layout/Footer'
import Content from './Layout/Content'
export default {
  name: 'Landing',
  components: {
    Header,
    Footer,
    Content
  },
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
