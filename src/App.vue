<template>
  <Header />
  <router-view />
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <HelloWorld2 />
  <HelloWorld3 />
  <HelloWorld4 />
  <HelloWorld5 />
  <HelloWorld6 />
  <HelloWorld7 />
  <Footer />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorld2 from './components/HelloWorld2.vue'
import HelloWorld3 from './components/HelloWorld3.vue'
import HelloWorld4 from './components/HelloWorld4.vue'
import HelloWorld5 from './components/HelloWorld5.vue'
import HelloWorld6 from './components/HelloWorld6.vue'
import HelloWorld7 from './components/HelloWorld7.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    HelloWorld2,
    HelloWorld3,
    HelloWorld4,
    HelloWorld5,
    HelloWorld6,
    HelloWorld7,
    Header,
    Footer
  }
}
</script>
