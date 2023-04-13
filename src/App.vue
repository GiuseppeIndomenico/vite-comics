<template>
  <header class="bg-light"><componentHeader/></header>
  <main>
    <section class="bg-dark"><componentMain1/></section>
    <section class="bg-primary"><componentMain2/></section>
  </main>
  <footer>
    <section class="gi-bg"> <componentFooter1/></section>
    <section class="bg-dark"> footer</section>
  </footer>

</template>

<script>
import componentHeader from './components/componentHeader.vue';
import componentMain1 from './components/componentMain1.vue';
import componentMain2 from './components/componentMain2.vue';
import componentFooter1 from './components/componentFooter1.vue';
  export default {
    components:{
      componentHeader,
      componentMain1,
      componentMain2,
      componentFooter1,
    }
  }
</script>

<style lang="scss" scoped>
.gi-bg{
  width: 100%;
  height: 600px;
  background-image: url(./assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}

</style>