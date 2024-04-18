<script setup>

</script>

<template>
  <h2> Frameworks </h2>

<div class="frameworksGrid">

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/django-logo-icon.webp" max-width="100%" max-height="100%" title="Django"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/express-js-icon.webp" max-width="100%" max-height="100%" title="Express JS"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/react-js-icon.webp" max-width="100%" max-height="100%" title="React JS"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/react-native-app-icon.webp" max-width="100%" max-height="100%" title="React Native"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/vue-js-icon.webp" max-width="100%" max-height="100%" title="Vue JS"/>

</div>




</div>
</template>

<style scoped>
.frameworksGrid {
  display:grid;
  grid-template-columns: repeat(4, 25% [col-start]);
  grid-template-rows: repeat(2, 30% [row-start]);
 
  margin-bottom: 10%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
}

.frameworksIcon {
  display: flex;
  flex-direction: column;
  
  
  margin-top: 10%;
}

h2 {
  font-size: 2em;
  color:white;
}

</style>
