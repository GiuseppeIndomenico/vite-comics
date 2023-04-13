<template>
  <header class="bg-light"><componentHeader/></header>
  <main>
    <section class="bg-dark"><componentMain1/></section>
    <section class="bg-primary">seconda section</section>
  </main>
  <footer>
    <section> prima section footer con immagine</section>
    <section class="bg-dark"> footer</section>
  </footer>

</template>

<script>
import componentHeader from './components/componentHeader.vue';
import componentMain1 from './components/componentMain1.vue';
  export default {
    components:{
      componentHeader,
      componentMain1,
    }
  }
</script>

<style lang="scss" scoped>


</style>