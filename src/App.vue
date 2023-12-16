<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'


</script>

<template>
  <div align="center">
  <h1> Sean Kuehl </h1>
  <img :src="logo" />
  </div>
  
  <div align="center">
  <h3> Languages </h3>
  
  <div style="display:grid;grid-template-columns: repeat(3, 60px [col-start]);grid-template-rows: repeat(3, 20px [row-start]);">
  <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
  <p>hello</p>
  <p>hello</p>
  <p>hello</p>
  <p>hello</p>
  <p>hello</p>
  </div>
  
  </div>

  
</template>

<style scoped>

h1 {
	vertical-align: text-top;
	font-size: 40px;
	color: Aquamarine;
}

</style>
