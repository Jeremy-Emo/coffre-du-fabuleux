<template>
  <p class="col text-center">Version {{ version }}</p>
</template>

<script>
export default {
  name: "my-footer",
  data () {
    return {
      version: process.env.VERSION
    }
  }
}
</script>

<style scoped>

</style>
