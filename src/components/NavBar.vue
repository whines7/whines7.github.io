<!--Header component with links to other parts of the doc-->
<template>
  <nav class="navbar fixed-top navbar-expand navbar-dark">
    <div class="container flex justify-between items-center pt-2">
      <div class="navbar-header">
        <a class="navbar-brand font-weight-bold" href="#">William Hines
          <span class="text-success">.</span>
        </a>
      </div>
      <ul class="nav navbar-nav mb-2 mb-lg-0">
        <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
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

<style>

</style>