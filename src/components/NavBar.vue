<!--Header component with links to other parts of the doc-->
<template>
  <nav class="navbar fixed-top navbar-expand navbar-dark bg-dark">
    <div class="container-fluid justify-content-center">
      <div class="navbar-header">
        <a class="navbar-brand" href="#">Will Hines</a>
      </div>
      <ul class="nav navbar-nav mb-2 mb-lg-0">
        <li class="nav-item"><a href="#" class="nav-link active" aria-current="page">Home</a></li>
        <li class="nav-item"><a href="#skills" class="nav-link">Skills</a></li>
        <li class="nav-item"><a href="#projects" class="nav-link">Projects</a></li>
        <li class="nav-item"><a href="#links" class="nav-link">Links</a></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  components: {
  }
}
</script>

<style scoped>
nav .navbar-nav li a{
  color: white;
  }
</style>