<template>
  <v-app>
    <AppBar/>
    <v-main>
      <router-view/>
    </v-main>
    <FooterBar/>
  </v-app>
</template>

<script>
import AppBar from './components/AppBar'
import FooterBar from './components/FooterBar'

export default {
  name: 'App',
  components: {
    AppBar,
    FooterBar
  },
  data: () => ({
    //
  }),
};
</script>

<style scoped>
*{
  background: darkgrey;
}
</style>