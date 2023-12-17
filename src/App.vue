<script setup>
import LanguagesSection from './components/LanguagesSection.vue';
import FrameworksSection from './components/FrameworksSection.vue';
import TechnologiesSection from './components/TechnologiesSection.vue';
import OpenSourceContribs from './components/OpenSourceContributions.vue';
import SocialsAndContacts from './components/SocialsAndContacts.vue';
</script>

<template>
  <body>
  <div class="topToBottom">
  <h1> Sean Kuehl </h1>

  <div align="center">
  <p> Hi, my name is Sean and I'm a Software Developer interested in Web Development and exploring new technologies. </p>
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

.topToBottom {
  display: flex;
  flex-direction: column;
}

h1 {
	font-size: 80px;
  margin-top: 5%;
  margin-left: 30%;
  margin-bottom: 10%;
	color: Aquamarine;
}

h3 {
  font-size: 30px;
  color:white;
}

h2 {
  color: lightgreen;
}

p {
  font-size: 30px;
  color: lightgreen;
  margin-bottom:10%;
}

body {
  background-image: url(https://media.giphy.com/media/U3qYN8S0j3bpK/giphy.gif)
}

</style>
