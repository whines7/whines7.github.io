<template>
  <div class="about text-light" id="about">
    <div class="container">
      <div class="row mt-3">
        <p>
          Hi, I'm William (Will) Hines, a recent graduate with an enthusiasm for technology and a passion for learning. My degree is in Criminal Justice, but I have taken many Computer Science classes. Recently, I have also finished the CompTIA A+ certification.
        </p>
        <br />
        <p>
          Some of my hobbies that don't involve technology include: travel, basketball and visiting art museums.
        </p>
      </div>
      <div class="row justify-content-center py-4">
          <img src="../../../assets/Attonfull.jpg" alt="Selfie" class="img-thumbnail" id="selfPicture" />
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
p {
  font-size: 2rem;
}

#selfPicture {
  width: 500px;
  height: 400px;
}
</style>