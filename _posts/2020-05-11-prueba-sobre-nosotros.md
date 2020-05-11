---
Title: Prueba formato sobre nosotros
author_profile: true
---


Voy a probar a ver si me salen las columnas
La info sale de [aquí](https://www.educative.io/edpresso/how-to-create-columns-in-html)

Hemos reunido aquí a distintas disciplinas científicas para demostrar que la Ciencia está en todas partes, y no sólo entre tubos de laboratorio y pizarras llenas de fórmulas.

¿Quiénes somos?

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>


<div class="row">
  <div class="column" style="background-color:#FFFFFF;">
    <h2> Inés Martínez Martín (@imartinesmartin)</h2>
    <p>Enamorada de la Ciencia, los viajes y los buenos bares (y de cualquier combinación de ellos). Graduada en Bioquímica, máster en Biofísica y eterna aprendiz de las bases físicas que dirigen los procesos biológicos. #BeerLover</p>
  </div>
  <div class="column" style="background-color:#FFFFFF;">
    <h2>Jaime Sáez-Mollejo</h2>
    <p>Amante de la montaña, la naturaleza y de vez en cuando intento aprender a tocar el piano. Soy graduado en Física y estoy dando   mis primeros pasos para entender el comportamiento de los electrones. #HikingLover</p>
  </div>
</div>

</body>
