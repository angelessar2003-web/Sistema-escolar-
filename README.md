<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Colegio Discovery - Inicio</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial, sans-serif;}
body{background:#f5f5f5;}
header{background:#556B2F;color:white;padding:20px;text-align:center;font-size:30px;font-weight:bold;}
nav{display:flex;justify-content:center;gap:25px;padding:15px;background:#3f4f22;}
nav a{color:white;text-decoration:none;font-size:18px;font-weight:600;}
nav a:hover{color:#ffd000;}
.hero{height:450px;background:url('https://images.pexels.com/photos/414595/pexels-photo-414595.jpeg') center/cover no-repeat;
display:flex;align-items:center;justify-content:center;color:white;text-shadow:2px 2px 10px rgba(0,0,0,0.7);}
.hero h1{font-size:48px;}
.section{padding:60px 20px;text-align:center;}
.section h2{font-size:36px;color:#556B2F;margin-bottom:15px;}
.section p{font-size:18px;color:#444;width:75%;margin:10px auto;}
.services{display:flex;flex-wrap:wrap;justify-content:space-around;gap:25px;margin-top:30px;}
.card{background:white;padding:25px;border-radius:10px;box-shadow:0 4px 10px rgba(0,0,0,0.1);width:290px;}
.card h3{color:#556B2F;margin-bottom:10px;}
.card p{font-size:16px;color:#333;}
footer{background:#556B2F;color:white;padding:20px;text-align:center;margin-top:40px;}
@media(max-width:768px){
.services{flex-direction:column;align-items:center;}
}
</style>
</head>
<body>

<header>🧑‍🎓 Colegio Discovery</header>

<nav>
<a href="#inicio">Inicio</a>
<a href="#nosotros">Nosotros</a>
<a href="#servicios">Servicios</a>
<a href="#contacto">Contacto</a>
</nav>

<div class="hero" id="inicio">
<h1>Bienvenido a Colegio Discovery</h1>
</div>

<section class="section" id="nosotros">
<h2>¿Quiénes somos?</h2>
<p>Somos un colegio comprometido con la educación integral de nuestros estudiantes, fomentando valores, aprendizaje y habilidades para la vida. Nuestro enfoque es formar personas críticas, responsables y creativas.</p>
</section>

<section class="section" id="servicios">
<h2>Nuestros servicios</h2>
<div class="services">

<div class="card">
<h3>📚 Educación Inicial</h3>
<p>Programas adaptados con enfoque lúdico para fortalecer las bases del conocimiento desde los primeros años.</p>
</div>

<div class="card">
<h3>📖 Educación Primaria</h3>
<p>Desarrollo académico sólido combinado con valores y habilidades sociales para la vida escolar y personal.</p>
</div>

<div class="card">
<h3>🎓 Educación Media</h3>
<p>Planes de estudio dinámicos para preparar a nuestros estudiantes hacia su futuro académico y profesional.</p>
</div>

</div>
</section>

<section class="section" id="contacto">
<h2>Contáctanos</h2>
<p>¿Deseas más información? Escríbenos a <strong>info@colegiodiscovery.edu.gt</strong> o llámanos al <strong>+502 1234-5678</strong>.</p>
</section>

<footer>
<p>© 2026 Colegio Discovery. Todos los derechos reservados.</p>
</footer>

</body>
</html>
