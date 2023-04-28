<template>
  <HeaderApp />
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld2 msg="Welcome to Your Vue.js App"/>
  <OtherScreen />
    
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorld2 from './components/HelloWorld2.vue'
import OtherScreen from './components/OtherScreen.vue'
import HeaderApp from './components/HeaderApp.vue'

export default{
  name: 'App',
  components: {
    HeaderApp,
    HelloWorld,
    HelloWorld2,
    OtherScreen,
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
  margin-top: 60px;
}
</style>
