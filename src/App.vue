<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloWorld from './components/HelloWorld.vue'

const x = {
a: [],
b: 1,
c: {},
d: 2
}
console.log(x) // eslint-disable-line no-console

@Component({
  components: {
    HelloWorld
  }
})
export default class App extends Vue {

foo() {
const x = {
a: [],
b: 1,
c: {},
d: 2
}
return x;
}

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
