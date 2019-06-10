<template>
  <section id="app"  class="container-fluid">
      <div class="jumbotron">
        <h1 class="display-4">Images</h1>
        <p class="lead"> Picture </p>
      </div>
      <page-header pagetitle ="Images"  pagelead = "Picture"></page-header>
      <navbar />
      <imageslides />
      <foodtiles />

  </section>
</template>

<script>
import navbar from '~/components/navbar.vue'
import imageslides from '~/components/image-slides.vue'
export default {
  components: {
    navbar,
    imageslides,

  }
}
</script>

<style>
*{
  text-align: center;
}

</style>
