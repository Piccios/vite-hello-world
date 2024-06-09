<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  components:
  {
    AppTitle,
    AppHero
  },
  data() {
    return {

    }
  },
  methods:{

  }, 
  created(){

  }
}
</script>

<template>
  <header>
    <AppTitle />
  </header>
<main>
  <section class="jumbotron">
    <AppHero />
  </section>
</main>

</template>

<style scoped>

</style>
