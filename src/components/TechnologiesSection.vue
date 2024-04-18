<script setup>

</script>

<template>
  
<h2> Technologies </h2>

<div class="technologiesGrid">

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/adobe-xd-icon.webp" max-width="100%" max-height="100%" title="Adobe Xd"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/github-icon.webp" max-width="100%" max-height="100%" title="Github"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/git-icon.webp" max-width="100%" max-height="100%" title="Git"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/godot-game-engine-icon-1.webp" max-width="100%" max-height="100%" title="Godot Game Engine"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/linux-icon.webp" max-width="100%" max-height="100%" title="Linux"/>

</div>

<div class="technologiesIcon" align="center">
<img src="../assets/technologies/virtual-machine-icon.webp" max-width="100%" max-height="100%" title="Virtual Machines"/>

</div>




</div>
</template>

<style scoped>
h2 {
  font-size: 2em;
  color:white;
}


.technologiesIcon {
  display: flex;
  flex-direction: column;
  margin-top: 10%;
}

.technologiesGrid {
  display:grid;
  grid-template-columns: repeat(3,30% [col-start]);
  grid-template-rows: repeat(3, 30% [row-start]);
  
  margin-bottom: 10%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
}

</style>