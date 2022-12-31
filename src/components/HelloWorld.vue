<template>
  <div class="header">
  <a href="#default" class="logo"> <img src="../assets/logoODMBordes.png" alt=""></a>
  <div class="header-right">
    <a class="active" href="#inicio">Inicio</a>
    <a href="#contacto">Contacto</a>
    <a href="#nosotros">Nosotros</a>
  </div>
</div>
<h1>AHORRA EN LOGÍSTICA HASTA UN 60%</h1>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  overflow: hidden;
  background-color: #f1f1f1;
  padding: 20px 10px;
}

.header a {
  float: left;
  color: black;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  line-height: 25px;
  border-radius: 4px;
}

.header a.logo {
  font-size: 25px;
  font-weight: bold;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: dodgerblue;
  color: white;
}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  .header-right {
    float: none;
  }
}
h1 {
  border: 2px solid powderblue;
  padding: 30px;
}
</style>
