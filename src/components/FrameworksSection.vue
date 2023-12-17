<script setup>

</script>

<template>
  <h3> Frameworks </h3>

<div class="frameworksGrid">

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/django-logo-icon.webp" width="100" height="100" title="Django"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/express-js-icon.webp" width="100" height="100" title="Express JS"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/react-js-icon.webp" width="100" height="100" title="React JS"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/react-native-app-icon.webp" width="100" height="100" title="React Native"/>

</div>

<div class="frameworksIcon" align="center">
<img src="../assets/frameworks/vue-js-icon.webp" width="100" height="100" title="Vue JS"/>

</div>




</div>
</template>

<style scoped>
.frameworksGrid {
  display:grid;
  grid-template-columns: repeat(3, 300px [col-start]);
  grid-template-rows: repeat(2, 150px [row-start]);
 
  margin-bottom: 10%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
}

.frameworksIcon {
  display: flex;
  flex-direction: column;
  margin-left:80%;
  
  margin-top: 10%;
}

h3 {
  font-size: 30px;
  color:white;
}

</style>
