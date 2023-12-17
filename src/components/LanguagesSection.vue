<script setup>

</script>

<template>
  <h3> Languages </h3>
  
  
  
  <div class="languagesGrid">

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/css-icon.webp" width="50" height="50" title="CSS"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/html-icon.webp" width="50" height="50" title="HTML"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/c-program-icon.webp" width="50" height="50" title="C"/>
  
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/c-plus-plus-programming-language-icon.webp" width="50" height="50" title="C++"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/c-sharp-programming-language-icon.webp" width="50" height="50" title="C#"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/java-programming-language-icon.webp" width="50" height="50" title="Java"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/javascript-programming-language-icon.webp" width="50" height="50" title="Javascript"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/python-programming-language-icon.webp" width="50" height="50" title="Python"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/mysql-icon.webp" width="50" height="50" title="Mysql"/>
    
    </div>

    <div class="languagesIcon" align="center">
    <img src="../assets/languages/godot-game-engine-icon.webp" width="50" height="50" title="Gdscript"/>
    
    </div>

  </div>
</template>

<style scoped>
.languagesGrid {
  display:grid;
  grid-template-columns: repeat(4, 300px [col-start]);
  grid-template-rows: repeat(3, 150px [row-start]);
  margin-left: 0;
  border-style: solid;
  border-color: Chartreuse;
  background-color: LightSteelBlue;
  margin-bottom: 10%;
}

.languagesIcon {
  
  display: flex;
  flex-direction: column;
  margin-left:35%;
  
  margin-top: 10%;
  
}

h3 {
  font-size: 30px;
  color:white;
}

</style>
