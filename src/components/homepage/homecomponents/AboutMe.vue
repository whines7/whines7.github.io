<template>
  <div class="about text-light" id="about">
    <div class="container">
      <div class="row justify-content-center py-4">
          <img src="../../../assets/Attonfull.jpg" alt="Selfie" class="img-thumbnail" id="selfPicture" />
      </div>
      <div class="row">
        <h1>About</h1>
      </div>      
      <div class="row">
        <p>
          I'm currently a student in my Senior year studying Computer Science at Southern Illinois University Edwardsville.
          At the moment I am expected to graduate in the Spring of 2023.
          My interest in programming stems from my avid use of technology in daily life.
          I began programming as a way to create things that help me in all different facets of life, and I'm passionate about using my knowledge to help others as well.
        </p>
        <br />
        <p>
          Besides programming my hobbies include: travel, basketball, weightlifting, gaming, and visiting art museums. I have a minor in Art History.
        </p>
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
h1 {
  font-size: 3.5rem;
}

p {
  font-size: 2rem;
}

#selfPicture {
  width: 500px;
  height: 400px;
}
</style>