<script setup>

</script>

<template>
  
<h3> Technologies </h3>

<div class="technologiesGrid">

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/adobe-xd-icon.webp" width="100" height="100" title="Adobe Xd"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/github-icon.webp" width="100" height="100" title="Github"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/git-icon.webp" width="100" height="100" title="Git"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/godot-game-engine-icon-1.webp" width="100" height="100" title="Godot Game Engine"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/linux-icon.webp" width="100" height="100" title="Linux"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/virtual-machine-icon.webp" width="100" height="100" title="Virtual Machines"/>

</div>




</div>
</template>

<style scoped>
h3 {
  font-size: 30px;
  color:white;
}


.technologiesIcon {
  display: flex;
  flex-direction: column;
  margin-left:60%;
  
  margin-top: 10%;
}

.technologiesGrid {
  display:grid;
  grid-template-columns: repeat(3, 300px [col-start]);
  grid-template-rows: repeat(2, 150px [row-start]);
  
  margin-bottom: 10%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
}

</style>