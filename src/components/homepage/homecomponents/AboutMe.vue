<template>
  <div class="about text-light" id="about">
    <div class="container mt-5">
      <div class="row">
        <div class="col">
          <div class="row">
            <h1>
              Hello, I'm
            </h1>
          </div>
          <div class="row text-success">
            <h1>
              Will Hines
            </h1>
          </div>
          <div class="row mt-4">
            <h4>
              Recent graduate with a passion for technology and learning.
            </h4>
          </div>
          <div class="row mt-4">
            <div class="col sm-4">
              <a target="_blank" href="https://drive.google.com/file/d/1ivMAK9KVlnRY-hKwfGja4N8md-14wiSb/view?usp=sharing" class="btn btn-lg btn-outline-success" role="button">
                Résumé
                <i class="fa-solid fa-file-lines"></i>
              </a>
            </div>
            <div class="col sm-4">
              <a href="mailto:bhines7@gmail.com" class="btn btn-lg btn-outline-success" role="button">
                Email Me
                <i class="fa-solid fa-envelope"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="col">
          <img src="../../../assets/Attonfull.jpg" class="border border-success rounded-circle" alt="Selfie" id="selfPicture" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'AboutMe',
    components: {
    }
  }
</script>

<style scoped>
  #selfPicture {
    width: 500px;
    height: 400px;
  }
</style>