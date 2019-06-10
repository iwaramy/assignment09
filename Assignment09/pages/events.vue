<template lang="html">
  <div class="container-fluid">
    <div class="jumbotron">
    <h1 class="display-4">Images</h1>
    <p class="lead"> Picture </p>
    </div>
    <page-header pagetitle ="Images"  pagelead = "Picture"></page-header>
    <navbar />
    <h1>Upcoming Events</h1>
    <eventstable />
  </div>
</template>

<script>
import navbar from '~/components/navbar.vue'
import eventstable from '~/components/eventstable.vue'

export default {
      components :{
          navbar,
          eventstable,
      }
}
</script>

<style lang="css" scoped>
*{
  text-align: center;
}
</style>
