<template>
  <div id="projects" class="projects text-success mt-5">
    <div class="container">
      <div class="row">
        <h1>Projects</h1>
      </div>
      <div class="row">
        <h5>(And other small things I've worked on.)</h5>
      </div>
      <div class="row mt-5">
        <div class="col-sm-6">
          <img src="../../assets/PersonalWebsite.png" class="border border-success img-fluid" />
          <h3>Personal Website</h3>
          <p>
            This website is my personal portfolio. It was built using Vue.js and Bootstrap.
            It is hosted on GitHub Pages and the source code can be found on my GitHub.
          </p>
        </div>
        <div class="col-sm-6">
          <i class="fa-solid fa-server fa-5x pt-5 pb-5"></i>
          <h3>Home Server</h3>
          <p>
            I turned an old computer into a home server to host various services such as a media server, password manager, and a personal cloud.
            This helps me continuously learn about networking and server management at home.
          </p>
        </div>
      </div>
      <div class="row mt-5 justify-content-center">
        <div class="col-sm-6">
          <img src="../../assets/SliderProgram.png" class="border border-success" id="sliderPicture" />
          <h3>Slider Helper</h3>
          <p>
            Created a small tool while learning C# that automates a click-intensive task in a game I play to help prevent repetitive strain injuries.
            This program has been used by over 100 people.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyProjects',
  components: {
  }
}
</script>

<style scoped>

  #sliderPicture {
    width: 300px;
    height: 300px;
  }

</style>