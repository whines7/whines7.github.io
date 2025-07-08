<template>
  <div class="not-found text-success mt-5">
    <div class="row h-100 justify-content-center align-items-center">
      <h1>404 Not Found</h1>
      <h3>Sorry, the page you are looking for could not be found.</h3>
    </div>
  </div>
</template>

<script>

export default {
  name: 'NotFound',
  components: {
  }
}
</script>

<style scoped>
h1 {
  font-size: 8rem;
}

.not-found {
  min-height: 100vh;
}

</style>