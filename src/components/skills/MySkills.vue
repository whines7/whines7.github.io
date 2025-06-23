<template>
  <div id="skills" class="skills text-danger">
    <div class="container">
        <div class="row">
            <h1>My Skills</h1>
        </div>
        <div class="row py-3">
          <div class="col-sm-6">
            <h1 id="cSharp">C#</h1>
            <div class="text-light">
              <h3>C#</h3>
              <p>
                I have over 3 years of experience working with C#. In my work at Foresight, 
                C# was the primary language used for back-end development. I have additional experience with the language from my Software Development class,
                as well as some of my projects such as (Clue solver).
                </p>
            </div>
          </div>
          <div class="col-sm-6">
            <h1 id="cPlusPlus">C++</h1>
            <div class="text-light">
              <h3>C, C++</h3>
              <p>
                I have a reasonable amount of experience in both C and C++ from the higher level classes I have taken.
              </p>
            </div>
          </div>
        </div>
        <div class="row py-3">
          <div class="col-sm-6">
            <i class="fa-brands fa-java fa-5x py-2"></i>
            <div class="text-light">
              <h3>Java</h3>
              <p>
                Java was the first language I learned. While I have not used it as much recently, I consider myself proficient in it due to
                using it in many classes as well as in some of my early basic personal projects.
              </p>
            </div>
          </div>
          <div class="col-sm-6">
            <i class="fa-brands fa-python fa-5x py-2"></i>
            <div class="text-light">
              <h3>Python</h3>
              <p>
                I have some familiarity with python. It was briefly used in my time at Foresight as part of an in-house app until that app was discontinued.
                My first working version of (Clue Solver) was also created in python.
              </p>
            </div>
          </div>
        </div>
        <div class="row py-3">
          <div class="col-sm-6">
            <i class="fa-brands fa-vuejs fa-5x py-2"></i>
            <div class="text-light">
              <h3>Vue.js</h3>
              <p>
                Vue.js is one of the newer frameworks I've learned. It was used as the primary front-end framework for building this website!
              </p>
            </div>
          </div>
          <div class="col-sm-6">
            <i class="fa-brands fa-react fa-5x py-2"></i>
            <div class="text-light">
              <h3>React</h3>
              <p>
                React was used for the front-end of a part of an internal tool that I helped create during my work at Foresight.
              </p>
            </div>
          </div>
        </div>
        <div class="row py-3">
          <div class="col-sm-6">
            <i class="fa-solid fa-code fa-5x py-2"></i>
            <div class="text-light">
              <h3>Javascript, Html, CSS</h3>
              <p>
                I have multiple years of experience with webdev, including full stack development experience from my time at Foresight.
              </p>
            </div>
          </div>
          <div class="col-sm-6">
            <i class="fa-solid fa-database fa-5x py-2"></i>
            <div class="text-light">
              <h3>Microsoft SQL Server</h3>
              <p>
                I have experience working with databases storing information on hundreds of different buildings for many customers during my time at Foresight.
              </p>
            </div>
          </div>         
        </div>
    </div>
  </div> 
</template>

<script>
export default {
  name: 'MySkills',
  components: {
  }
}
</script>

<style scoped>
h1 {
  font-size: 5rem;
}

h3{
  font-size: 2.5rem;
}

p {
  font-size: 1.3rem;
}

#cSharp, #cPlusPlus {
  text-shadow: none;
}

</style>