---
Title: Prueba formato sobre nosotros WIDE
author_profile: true
classes: wide
---


Voy a probar a ver si me salen las columnas.
La info sale de [aquí](https://www.w3schools.com/howto/howto_css_two_columns.asp)
* En principio he definido el tamaño de imagen, pero pasa de mí. En el eje x se ajustan a la columna, así que bien, pero en el y...cada una es de su padre y de su madre. Se me ocurren dos opciones:
    * Arreglar nuestras fotos para que sean iguales.
    * Que la imagen esté en una fila diferente del texto. Aunque claro, si tu imagen es más corta que la de el de al lado quedará un espacio blanco entre imagen y texto. A mí me parece feo...
* No me he puesto, pero se puede hacer que esto sea "responsive". Es decir, que si la ventana es pequeña dejan de ser dos columnas para ser una y que se vea mejor. Puedo intentarlo. 
* Me falta poner el link del Twitter de Inés, alguien más quiere poner el suyo? (Me jode el alineado, maja). 
* Se puede cambiar el tamaño del nombre, el color del fondo...

---
Hemos reunido aquí a distintas disciplinas científicas para demostrar que la Ciencia está en todas partes, y no sólo entre tubos de laboratorio y pizarras llenas de fórmulas.

¿Quiénes somos?

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
/* This is used to define the class that enables image centering */
   .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
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
    <h3> Inés Martínez Martín (@imartinesmartin)</h3>
    <p><img  style="margin: auto" src="https://github.com/JuditSastre/test_blog/blob/master/assets/images/ines1.jpg?raw=true" class="center" width="60%"><br>Enamorada de la Ciencia, los viajes y los buenos bares (y de cualquier combinación de ellos). Graduada en Bioquímica, máster en Biofísica y eterna aprendiz de las bases físicas que dirigen los procesos biológicos.<br> <b>#BeerLover</b></p>
  </div>
  <div class="column" style="background-color:#FFFFFF;">
    <h3>Jaime Sáez-Mollejo</h3>
    <p><img src="https://github.com/JuditSastre/test_blog/blob/master/assets/images/jaime1.jpg?raw=true" width="400" height="400"><br>Amante de la montaña, la naturaleza y de vez en cuando intento aprender a tocar el piano. Soy graduado en Física y estoy dando   mis primeros pasos para entender el comportamiento de los electrones.<br><b>#HikingLover</b></p>
  </div>
</div>
<div class="row">
  <div class="column" style="background-color:#FFFFFF;">
    <h3>Laura Pérez-Chirinos</h3>
    <p><img src="https://github.com/JuditSastre/test_blog/blob/master/assets/images/laura1.jpg?raw=true" width="400" height="400"><br>¿La mejor manera de evadir mi mente? El piano y la pintura. Amante de los viernes por la noche y de retos nuevos.<br>Graduada en Biotecnología y apasionada de los modelos matemáticos que describen la biología. En un intento de fusionar la investigación computacional con la experimental.<br><b>#NoTengoHashtag</b></p>
  </div>
   <div class="column" style="background-color:#FFFFFF;">
      <h3>Judit Sastre Pozo</h3>
      <p><img src="https://github.com/JuditSastre/test_blog/blob/master/assets/images/judit1.jpg?raw=true" width="400" height="400"><br>Historias trepidantes, ciencia a mogollón y cacharros alucinantes. De pequeña quería ser escritora de ciencia ficción… al final estudié Química. Sin embargo, no renuncié a los cacharros chulos, por eso hice un máster en Biofísica. Ni a las buenas historias… y aquí estamos.<br><i>¿Qué es la vida?</i> (Erwin Schrödinger) versus <i>La última pregunta</i> (Isaac Asimov)<br><b>#SciFiVsSciFacts</b></p>
   </div>
</div>
<div class="row">
  <div class="column" style="background-color:#FFFFFF;">
    <h3>Adrián Candelas Baonza</h3>
    <p><img src="https://vignette.wikia.nocookie.net/liverpoolfc/images/2/24/Adrian2019.jpeg/revision/latest?cb=20190807042615" width="400" height="400"><br>Mis noches las alterno entre el laboratorio y mi vida social. Las mañanas son para descansar de toda la vida. Biólogo por la Univ. Autónoma de Madrid, máster en investigación multidisciplinar por la Univ. Pompeu Fabra y actualmente realizando un doctorado (PhD) en Terapia Celular por la Universidad de la Sorbonna (CytomorphoLab). Soy el raro del grupo, el que prefiere un vino a una cerveza.<b><br>#TeamWine</b></p>
  </div>
  <div class="column" style="background-color:#FFFFFF;">
    <h3>Dani</h3>
    <p><img src="https://imagenes.20minutos.es/files/image_656_370/files/fp/uploads/imagenes/2020/03/25/el-acator-dani-rovira.r_d.2572-581.jpeg" width="400" height="400"><br>Dani tiene sus sueños, miedos e incertidumbres, como los demás.<br>Incluso tiene apellidos, aunque Judit aún no los sabe. <b>#SoyNuevo</b></p>
  </div>
</div>

</body>
</html>
