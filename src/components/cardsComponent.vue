<template>
<div class="content">
   <div class="details">
       <h3>Choose a pokemon to get more information</h3>
   </div>
  <div class="contenedor__cards">
    <div class="card">
       <!-- <img src="../src/assets/001.png"> -->
    </div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <!-- <div class="card"></div> -->
  </div>
  <div class="button" style="text-align: center">
      <button class="btn btn-primary mt-1">Lood More</button>
  </div>
</div>
</template>

<style scoped>

.content {
    width: 70vw;
    height: 85vh;
}

.details {
    margin: 10px 10px;
}

.details h3 {
    font-weight: 500;
    font-size: 20px;
    letter-spacing: .3px;
}
.contenedor__cards {
    height: 80vh;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-evenly;
  overflow-y: auto;
}
.card {
  width: 320px;
  height: 330px;
  flex-shrink: 0;
  margin: 10px;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  border: 2px solid rgb(236, 230, 230);
  border-radius: 7px;
  transition-property: width height;
  transition-duration: 1s;
}

.card:hover {
  width: 330px;
  height: 340px;
}
</style>
