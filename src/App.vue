<template>
  <header class="bg-light"><componentHeader/></header>
  <main>
    <section class="bg-dark"><componentMain1/></section>
    <section class="bg-primary p-2"><componentMain2/></section>
  </main>
  <footer>
    <section class="gi-bg"> <componentFooter1/></section>
    <section class="gi-dark text-light"> <componentFooter2/></section>
  </footer>

</template>

<script>
import componentHeader from './components/componentHeader.vue';
import componentMain1 from './components/componentMain1.vue';
import componentMain2 from './components/componentMain2.vue';
import componentFooter1 from './components/componentFooter1.vue';
import componentFooter2 from './components/componentFooter2.vue';
  export default {
    components:{
      componentHeader,
      componentMain1,
      componentMain2,
      componentFooter1,
      componentFooter2,
    }
  }
</script>

<style lang="scss" scoped>
.gi-bg{
  width: 100%;
  height: 100%;
  background-image: url(public/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
};
.gi-dark{
  background-color: #333333;
}


</style>