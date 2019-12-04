<template>
  <div class="text-gray-700 bg-gray-300 font-light">
    <app-navbar></app-navbar>
    <nuxt />
  </div>
</template>

<script>
import AppNavbar from '~/components/AppNavbar'
export default {
  components: {
    AppNavbar
  }
}
</script>
<style></style>
