<template>
  <div id="info" class="info text-light">
    <div class="container">
      <div class="row">
        <div class="row justify-content-center py-1">
          <div class="col-sm-4">
              <a target="_blank" href="https://docs.google.com/document/d/1y7x-9CpWVAiUM7GsNYiOnCqw12RmKRYsXAkHONHUiuA/edit?usp=sharing" class="btn btn-lg btn-light" role="button">Resume</a>             
          </div>
            
        </div>
        <div class="row justify-content-center py-1">
          <div class="col-sm-4">
            <a href="#contact" class="btn btn-lg btn-light" role="button">Contact Me</a>
          </div>   
        </div>
        <div class="row justify-content-center py-4">
          <img src="../../../assets/Attonfull.jpg" alt="Selfie" class="img-thumbnail" id="selfPicture" />
        </div>
      </div>  
    </div>         
  </div>
</template>

<script>
export default {
  name: 'MyNameIsWill',
  components: {
  }
}
</script>

<style scoped>
  h1 {
    font-size: 5.5rem;
  }

  #selfPicture {
    height: 500px;
    width: 400px;
  }
</style>