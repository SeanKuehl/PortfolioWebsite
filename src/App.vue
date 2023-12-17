<script setup>
import HelloWorld from './components/HelloWorld.vue';
import TheWelcome from './components/TheWelcome.vue';





</script>

<template>
  <div class="topToBottom">
  <h1> Sean Kuehl </h1>

  <div align="center">
  <p> Hi, my name is Sean and I'm a Software Developer interested in Web Development and exploring new technologies. </p>
  </div>
  
  
  <div align="center">
  <h3> Languages </h3>
  
  
  
  <div class="languagesGrid">

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/css-icon.webp" width="50" height="50" title="CSS"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/html-icon.webp" width="50" height="50" title="HTML"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/c-program-icon.webp" width="50" height="50" title="C"/>
  
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/c-plus-plus-programming-language-icon.webp" width="50" height="50" title="C++"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/c-sharp-programming-language-icon.webp" width="50" height="50" title="C#"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/java-programming-language-icon.webp" width="50" height="50" title="Java"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/javascript-programming-language-icon.webp" width="50" height="50" title="Javascript"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/python-programming-language-icon.webp" width="50" height="50" title="Python"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/mysql-icon.webp" width="50" height="50" title="Mysql"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="./assets/languages/godot-game-engine-icon.webp" width="50" height="50" title="Gdscript"/>
    
    </div>

  </div>



  <h3> Frameworks </h3>

  <div class="frameworksGrid">

<div class="frameworksIcon" align="center">
<img src="./assets/frameworks/django-logo-icon.webp" width="100" height="100" title="Django"/>

</div>

<div class="frameworksIcon" align="center">
<img src="./assets/frameworks/express-js-icon.webp" width="100" height="100" title="Express JS"/>

</div>

<div class="frameworksIcon" align="center">
<img src="./assets/frameworks/react-js-icon.webp" width="100" height="100" title="React JS"/>

</div>

<div class="frameworksIcon" align="center">
<img src="./assets/frameworks/react-native-app-icon.webp" width="100" height="100" title="React Native"/>

</div>

<div class="frameworksIcon" align="center">
<img src="./assets/frameworks/vue-js-icon.webp" width="100" height="100" title="Vue JS"/>

</div>




</div>



<h3> Technologies </h3>

  <div class="technologiesGrid">

<div class="technologiesIcon" align="center">
<img src="./assets/technologies/adobe-xd-icon.webp" width="100" height="100" title="Adobe Xd"/>

</div>

<div class="technologiesIcon" align="center">
<img src="./assets/technologies/github-icon.webp" width="100" height="100" title="Github"/>

</div>

<div class="technologiesIcon" align="center">
<img src="./assets/technologies/git-icon.webp" width="100" height="100" title="Git"/>

</div>

<div class="technologiesIcon" align="center">
<img src="./assets/technologies/godot-game-engine-icon-1.webp" width="100" height="100" title="Godot Game Engine"/>

</div>

<div class="technologiesIcon" align="center">
<img src="./assets/technologies/linux-icon.webp" width="100" height="100" title="Linux"/>

</div>

<div class="technologiesIcon" align="center">
<img src="./assets/technologies/virtual-machine-icon.webp" width="100" height="100" title="Virtual Machines"/>

</div>




</div>


<h3> Links To Open Source Contributions </h3>



<div align="center">
  <a href="https://github.com/crownengine/crown/commits/master/?author=SeanKuehl">
<h2>Contributed to Crown game engine</h2>
</a>

</div>

<div align="center">
  <a href="https://github.com/drwhut/tabletop-club/commits/master/?author=SeanKuehl">
<h2>Contributed to Tabletop-club</h2>
</a>

</div>











  
  </div>

  </div>
  
</template>

<style scoped>


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
  margin-left: 5%;
  margin-bottom: 10%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
}

.frameworksGrid {
  display:grid;
  grid-template-columns: repeat(3, 300px [col-start]);
  grid-template-rows: repeat(2, 150px [row-start]);
  margin-left: 5%;
  margin-bottom: 10%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
}

.frameworksIcon {
  display: flex;
  flex-direction: column;
  margin-left:60%;
  
  margin-top: 10%;
}


.languagesGrid {
  display:grid;
  grid-template-columns: repeat(4, 300px [col-start]);
  grid-template-rows: repeat(3, 150px [row-start]);
  margin-left: 5%;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
  margin-bottom: 10%;
}

.topToBottom {
  
  display: flex;
  flex-direction: column;


}

.languagesIcon {
  
  display: flex;
  flex-direction: column;
  margin-left:25%;
  
  margin-top: 10%;
  
}

h1 {
  
	
	font-size: 80px;
  margin-top: 5%;
  margin-left: 35%;
  margin-bottom: 10%;
	color: Aquamarine;
}

h3 {
  font-size: 30px;
  color:white;
}

p {
  font-size: 20px;
  color: lightgreen;
  margin-left:5%;
  margin-bottom:10%;
}

</style>
