<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ciencias Aplicadas en Tecnologías Maker</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#f4f7fa;
}

header{
background:#39A900;
color:white;
padding:25px;
text-align:center;
}

header h1{
font-size:34px;
}

header p{
margin-top:10px;
font-size:18px;
}

nav{
display:flex;
justify-content:center;
background:#00304D;
}

nav button{

padding:18px 40px;
border:none;
background:#00304D;
color:white;
cursor:pointer;
font-size:18px;
transition:0.3s;

}

nav button:hover{
background:#39A900;
}

.tabcontent{

display:none;
padding:40px;

}

.card{

background:white;
padding:25px;
border-radius:12px;
box-shadow:0px 0px 10px rgba(0,0,0,.15);

}

.card h2{

color:#39A900;
margin-bottom:20px;

}

ul{

list-style:none;

}

li{

margin:15px 0;

}

a{

text-decoration:none;
color:#00304D;
font-size:18px;

}

a:hover{

color:#39A900;

}

footer{

background:#00304D;
color:white;
padding:15px;
text-align:center;
margin-top:30px;

}

</style>

</head>

<body>

<header>

<h1>Ciencias Aplicadas en Tecnologías Maker</h1>

<p>Repositorio de Material Académico</p>

</header>

<nav>

<button onclick="abrir('matematicas')">Matemáticas</button>

<button onclick="abrir('fisica')">Física</button>

<button onclick="abrir('investigacion')">Investigación</button>

</nav>

<!-- MATEMÁTICAS -->

<div id="matematicas" class="tabcontent">

<div class="card">

<h2>📘 Matemáticas Aplicadas</h2>

<ul>

<li><a href="pdf/guia1.pdf" target="_blank">📄 Guía 1. Operaciones Básicas</a></li>

<li><a href="pdf/guia2.pdf" target="_blank">📄 Guía 2. Conversión de Unidades</a></li>

<li><a href="pdf/guia3.pdf" target="_blank">📄 Guía 3. Geometría Aplicada</a></li>

<li><a href="pdf/guia4.pdf" target="_blank">📄 Guía 4. Estadística</a></li>

<li><a href="pdf/guia5.pdf" target="_blank">📄 Guía 5. Matemática Financiera</a></li>

</ul>

</div>

</div>

<!-- FÍSICA -->

<div id="fisica" class="tabcontent">

<div class="card">

<h2>⚙️ Física Aplicada</h2>

<ul>

<li><a href="pdf/fisica1.pdf" target="_blank">📄 Temperatura y Calor</a></li>

<li><a href="pdf/fisica2.pdf" target="_blank">📄 Cadena de Frío</a></li>

<li><a href="pdf/fisica3.pdf" target="_blank">📄 Electricidad Básica</a></li>

<li><a href="pdf/fisica4.pdf" target="_blank">📄 Energía y Potencia</a></li>

<li><a href="pdf/fisica5.pdf" target="_blank">📄 Sensores IoT</a></li>

</ul>

</div>

</div>

<!-- INVESTIGACIÓN -->

<div id="investigacion" class="tabcontent">

<div class="card">

<h2>🔬 Investigación Formativa</h2>

<ul>

<li><a href="pdf/investigacion1.pdf" target="_blank">📄 Método Científico</a></li>

<li><a href="pdf/investigacion2.pdf" target="_blank">📄 Formulación del Problema</a></li>

<li><a href="pdf/investigacion3.pdf" target="_blank">📄 Hipótesis y Variables</a></li>

<li><a href="pdf/investigacion4.pdf" target="_blank">📄 Marco Teórico</a></li>

<li><a href="pdf/investigacion5.pdf" target="_blank">📄 Proyecto Final</a></li>

</ul>

</div>

</div>

<footer>

Centro de Gestión de Mercados, Logística y Tecnologías de la Información<br>

Repositorio de Ciencias Aplicadas en Tecnologías Maker

</footer>

<script>

function abrir(nombre){

var tabs=document.getElementsByClassName("tabcontent");

for(var i=0;i<tabs.length;i++){

tabs[i].style.display="none";

}

document.getElementById(nombre).style.display="block";

}

document.getElementById("matematicas").style.display="block";

</script>

</body>

</html>
