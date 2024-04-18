<script setup>
import LanguagesSection from './components/LanguagesSection.vue';
import FrameworksSection from './components/FrameworksSection.vue';
import TechnologiesSection from './components/TechnologiesSection.vue';
import OpenSourceContribs from './components/OpenSourceContributions.vue';
import SocialsAndContacts from './components/SocialsAndContacts.vue';
</script>

<template>
  <body>
  <div>
    <div align="center">
      <h1> Sean Kuehl </h1>
    </div>
  

  <div align="center">
  <h3> Hi, my name is Sean and I'm a Software Developer interested in Web Development and exploring new technologies. </h3>
  </div>
  
  <div align="center">

    <LanguagesSection/>

    <FrameworksSection/>
  
    <TechnologiesSection/>

    <OpenSourceContribs/>
  
    <SocialsAndContacts/>

<h2 style="margin-top:20%;"> &#169; Sean Kuehl 2023</h2>
  
  </div>

  </div>
</body>
</template>

<style scoped>



h1 {
  font-size: 3em;
	color: Aquamarine;
}

h3 {
  font-size: 1em;
  color:white;
  margin-bottom:10%;
}

h2 {
  font-size: 2em;
  color: lightgreen;
  
}

p {
  
  color: lightgreen;
  margin-bottom:10%;
}

body {
  background-image: url(https://media.giphy.com/media/U3qYN8S0j3bpK/giphy.gif)
}

</style>
