<template>
  <div id="app">
    <navbar></navbar>
    <main>
      <router-view/>
    </main>
  </div>
</template>

<script>
import Navbar from '@/components/navbar.vue'

export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style lang="scss">
  @import './assets/sass/app.scss';
</style>

