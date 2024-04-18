<script setup>

</script>

<template>
  <h2> Languages </h2>
  
  
  
  <div class="languagesGrid">

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/css-icon.webp" max-width="1vw" max-height="1vh" title="CSS"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/html-icon.webp" max-width="1vw" max-height="1vh" title="HTML"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/c-program-icon.webp" max-width="1vw" max-height="1vh" title="C"/>
  
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/c-plus-plus-programming-language-icon.webp" max-width="1vw" max-height="1vh" title="C++"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/c-sharp-programming-language-icon.webp" max-width="1vw" max-height="1vh" title="C#"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/java-programming-language-icon.webp" max-width="1vw" max-height="1vh" title="Java"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/javascript-programming-language-icon.webp" max-width="1vw" max-height="1vh" title="Javascript"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/python-programming-language-icon.webp" max-width="1vw" max-height="1vh" title="Python"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/mysql-icon.webp" max-width="1vw" max-height="1vh" title="Mysql"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/godot-game-engine-icon.webp" max-width="1vw" max-height="1vh" title="Gdscript"/>
    
    </div>

  </div>
</template>

<style scoped>
.languagesGrid {
  
  display:grid;
  grid-template-columns: repeat(4, 25% [col-start]);
  grid-template-rows: repeat(3, 30% [row-start]);
 
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
  margin-bottom: 10%;
}

.languagesIcon {
  
  display: flex;
  flex-direction: column;
  
  
  margin-top: 10%;
  
}

h2 {
  font-size: 2em;
  color:white;
}

</style>
