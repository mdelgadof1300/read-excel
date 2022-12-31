<template>
    <div>
      <form action="#">
      <label for="lang">Origen</label>
      <br>
      <select name="select">
        <option value="value1"> Elegir opciones de origen</option>
        <option value="value2">recorrer valores</option>
        <option value="value3">Value 3</option>
      </select>
      <br>
      <label for="lang">Destino</label>
      <br>
      <select name="select">
        <option value="value1"> Elegir opciones de destino</option>
        <option value="value2">recorrer valores</option>
        <option value="value3">Value 3</option>
      </select>
      <input type="submit" value="Enviar" />
</form> </div>
</template>

<style>
 select {
        align-content: center;
        margin-bottom: 10px;
        margin-top: 10px;
        font-family: cursive, sans-serif;
        outline: 0;
        background: #0d47a1;
        color: #fff;
        border: 1px solid crimson;
        padding: 4px;
        border-radius: 9px;
      }</style>