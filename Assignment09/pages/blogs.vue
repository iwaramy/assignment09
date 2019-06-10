<template lang="html">
  <div class="container-fluid">
    <div class="jumbotron">
    <h1 class="display-4">Images</h1>
    <p class="lead"> Picture </p>
    </div>
    <page-header pagetitle ="Images"  pagelead = "Picture"></page-header>
    <navbar />
    <h1>Photography</h1>
    <blogtable />
  </div>
</template>

<script>
import navbar from '~/components/navbar.vue'
import blogtable from '~/components/blogtable.vue'
export default {
      components :{
          navbar,
          blogtable,
      }
}
</script>

<style lang="css" scoped>
*{
  text-align: center;
}
</style>
