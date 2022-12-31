<template>
    <div><div class="row">
  <div class="col">Sobre</div>
  <div class="col">Paquete 1kg</div>
  <div class="col">Paquete 1-10kg</div>
  <div class="col">Paquete 11-20kg</div>
  <div class="col">Paquete 21-30kg</div>
</div></div>
</template>

<style>
.row {
  display: flex;
  flex-wrap: wrap;
}

.col {
  flex: 1 0 18%; /* The important bit. This percentage decides your columns. 
 The percent can be px. It just represents your minimum starting width.
  */
  margin: 5px;
  background: #0d47a1;
  height: 50px;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
}</style>