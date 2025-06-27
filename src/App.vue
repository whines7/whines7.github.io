<template>
  <div id="app">
    <NavBar />
    <div class="screen pt-5 pb-4 bg-dark">
      <component :is="currentView" />
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HomePage from './components/homepage/HomePage.vue'
import NotFound from './components/notfound/NotFound.vue'
import MySkills from './components/skills/MySkills.vue'
import MyLinks from './components/links/MyLinks.vue'
import MyProjects from './components/projects/MyProjects.vue'

const routes = {
  '/': HomePage,
  'skills': MySkills,
  'links': MyLinks,
  'projects': MyProjects
}

export default {
  data() {
    return {
      currentPath: window.location.hash
    }
  },
  computed: {
    currentView() {
      return routes[this.currentPath.slice(1) || '/'] || NotFound
    }
  },
  mounted() {
    //Font Awesome implementation
    let faScript = document.createElement('script')
    faScript.setAttribute('src', "https://kit.fontawesome.com/044156b56d.js")
    faScript.setAttribute('crossorigin', "anonymous")
    document.head.appendChild(faScript)

    window.addEventListener('hashchange', () => {
      this.currentPath = window.location.hash
    })
  },
  name: 'App',
  components: {
    NavBar,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

h1 {
  text-shadow: 2px 0 0 #000, 0 -2px 0 #000, 0 2px 0 #000, -2px 0 0 #000;
}

p, h3 {
  text-shadow: 1px 0 0 #000, 0 -1px 0 #000, 0 1px 0 #000, -1px 0 0 #000;
}

.screen {
  min-height: 100vh;
}

</style>

