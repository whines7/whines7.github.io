<template>
  <div class="about text-light" id="about">
    <div class="container">
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
        </div>
        <div class="col">
            <img src="../../../assets/Attonfull.jpg" alt="Selfie" class="img-thumbnail" id="selfPicture" />
        </div>
      </div>
      <!--Removal in progress
      <div class="row mt-3">
        <p>
          Hi, I'm William (Will) Hines, a recent graduate with an enthusiasm for technology and a passion for learning. My degree is in Criminal Justice, but I have taken many Computer Science classes. Recently, I have also finished the CompTIA A+ certification.
        </p>
        <br />
        <p>
          Some of my hobbies that don't involve technology include: travel, basketball and visiting art museums.
        </p>
      </div>
      -->
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