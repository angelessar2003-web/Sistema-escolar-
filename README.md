# Sistema-escolar-
Escolar 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Colegio Mixto Bilingüe Discovery</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Colegio Mixto Bilingüe Discovery</h1>
</header>

<nav>
<button onclick="mostrar('estudiantes')">Estudiantes</button>
<button onclick="mostrar('pagos')">Pagos</button>
<button onclick="mostrar('notas')">Calificaciones</button>
</nav>

<section id="estudiantes">

<h2>Agregar Estudiante</h2>

<input id="nombre" placeholder="Nombre">
<input id="grado" placeholder="Grado">
<input id="seccion" placeholder="Sección">

<button onclick="agregarEstudiante()">Guardar</button>

<h3>Lista de Estudiantes</h3>
<ul id="listaEstudiantes"></ul>

</section>

<section id="pagos" class="oculto">

<h2>Registrar Pago</h2>

<input id="estudiantePago" placeholder="Nombre del estudiante">
<input id="tipoPago" placeholder="Tipo de pago">

<input id="monto" placeholder="Monto Q">

<button onclick="registrarPago()">Guardar Pago</button>

<ul id="listaPagos"></ul>

</section>

<section id="notas" class="oculto">

<h2>Registrar Calificaciones</h2>

<input id="estudianteNota" placeholder="Estudiante">

<input id="materia" placeholder="Materia">

<input id="nota" placeholder="Nota">

<button onclick="registrarNota()">Guardar Nota</button>

<ul id="listaNotas"></ul>

</section>

<script src="script.js"></script>

</body>
</html>

body{

font-family: Arial;

background:#f2f2f2;

margin:0;

}

.contenedor{

max-width:500px;

margin:auto;

background:white;

padding:20px;

min-height:100vh;

}

h1{

text-align:center;

}

input{

width:100%;

padding:12px;

margin-top:8px;

margin-bottom:8px;

border-radius:5px;

border:1px solid #ccc;

}

button{

width:100%;

padding:12px;

background:#2e7d32;

color:white;

border:none;

border-radius:5px;

margin-bottom:10px;

}

button:hover{

background:#1b5e20;

}

.tarjeta{

background:#f9f9f9;

padding:10px;

margin:5px 0;

border-radius:5px;

border:1px solid #ddd;

}
