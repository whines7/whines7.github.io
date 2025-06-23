<template>
  <div id="home">
    <MyNameIsWill />
    <AboutMe />
  </div>
</template>

<script>
import MyNameIsWill from './homecomponents/MyNameIsWill.vue'
import AboutMe from './homecomponents/AboutMe.vue'

export default {
  name: 'HomePage',
  components: {
    MyNameIsWill,
    AboutMe
  }
}
</script>
