<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Grupo Salud Integral Ayacucho</title>

<style>

:root{
--primario:#0f6efd;
--secundario:#00b4d8;
--verde:#25D366;
--fondo:#f5f8fb;
--texto:#2d3436;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:var(--fondo);
color:var(--texto);
}

header{
background:linear-gradient(135deg,#0f6efd,#00b4d8);
color:white;
padding:90px 20px;
text-align:center;
}

header h1{
font-size:3rem;
margin-bottom:15px;
}

header p{
font-size:1.2rem;
max-width:800px;
margin:auto;
}

.hero-btn{
display:inline-block;
margin-top:25px;
padding:15px 30px;
background:white;
color:#0f6efd;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

nav{
position:sticky;
top:0;
z-index:1000;
background:white;
box-shadow:0 2px 12px rgba(0,0,0,.1);
}

nav ul{
display:flex;
justify-content:center;
flex-wrap:wrap;
list-style:none;
}

nav a{
display:block;
padding:15px;
text-decoration:none;
color:#0f6efd;
font-weight:600;
}

nav a:hover{
background:#0f6efd;
color:white;
}

section{
padding:70px 20px;
max-width:1200px;
margin:auto;
}

.titulo{
text-align:center;
font-size:2rem;
margin-bottom:40px;
color:#0f6efd;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:20px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.card h3{
margin-bottom:10px;
color:#0f6efd;
}

.btn{
display:inline-block;
margin-top:15px;
padding:12px 20px;
background:var(--verde);
color:white;
text-decoration:none;
border-radius:50px;
font-weight:bold;
}

.farmacia{
background:white;
padding:40px;
border-radius:25px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.farmacia ul{
padding-left:20px;
margin-top:20px;
}

footer{
background:#0f6efd;
color:white;
text-align:center;
padding:30px;
}

.whatsapp{
position:fixed;
right:20px;
bottom:20px;
background:#25D366;
width:65px;
height:65px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:30px;
text-decoration:none;
color:white;
box-shadow:0 5px 15px rgba(0,0,0,.3);
}

@media(max-width:768px){

header h1{
font-size:2rem;
}

nav ul{
flex-direction:column;
}

}

</style>
</head>

<body>

<header>

<h1>Grupo Salud Integral Ayacucho</h1>

<p>
Atención integral para toda la familia.
Profesionales especializados comprometidos con tu bienestar.
</p>

<a class="hero-btn"
href="https://wa.me/5493517692619"
target="_blank">
Solicitar Turno
</a>

</header>

<nav>
<ul>

<li><a href="#especialidades">Especialidades</a></li>
<li><a href="#farmacia">Farmacia</a></li>
<li><a href="#contacto">Contacto</a></li>

</ul>
</nav>

<section id="especialidades">

<h2 class="titulo">Nuestras Especialidades</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1576091160550-2173dba999ef">
<div class="card-content">
<h3>Psicología</h3>
<p>Atención para niños, adolescentes y adultos.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1584515933487-779824d29309">
<div class="card-content">
<h3>Psicopedagogía</h3>
<p>Apoyo al aprendizaje y desarrollo integral.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1559757175-5700dde675bc">
<div class="card-content">
<h3>Fonoaudiología</h3>
<p>Evaluación y tratamiento del lenguaje y la comunicación.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1516549655169-df83a0774514">
<div class="card-content">
<h3>Nutrición</h3>
<p>Planes personalizados y educación alimentaria.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b">
<div class="card-content">
<h3>Kinesiología</h3>
<p>Rehabilitación física y recuperación funcional.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1629909613654-28e377c37b09">
<div class="card-content">
<h3>Odontología</h3>
<p>Prevención, diagnóstico y tratamientos odontológicos.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1631815588090-d4bfec5b1ccb">
<div class="card-content">
<h3>Medicina Generalista</h3>
<p>Control clínico, seguimiento y atención primaria.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1580281657527-47f249e8f4df">
<div class="card-content">
<h3>Niñez y Adolescencia</h3>
<p>Abordaje interdisciplinario para el desarrollo integral.</p>
<a class="btn" href="https://wa.me/5493517692619">Consultar</a>
</div>
</div>

</div>

</section>

<section id="farmacia">

<h2 class="titulo">Farmacia Cruz Verde</h2>

<div class="farmacia">

<p>
Un espacio pensado para brindar acompañamiento profesional y acceso a productos farmacéuticos esenciales.
</p>

<ul>
<li>Dispensación de medicamentos.</li>
<li>Control de glucemia.</li>
<li>Aplicación de inyectables.</li>
<li>Seguimiento farmacoterapéutico.</li>
<li>Asesoramiento personalizado.</li>
<li>Atención profesional.</li>
</ul>

<br>

<a class="btn"
href="https://wa.me/5493517692619">
Contactar Farmacia
</a>

</div>

</section>

<section id="contacto">

<h2 class="titulo">Contacto</h2>

<p style="text-align:center;font-size:1.2rem;">
WhatsApp: 3517692619
</p>

<br>

<div style="text-align:center;">

<a class="btn"
href="https://wa.me/5493517692619"
target="_blank">
Solicitar Turno
</a>

</div>

</section>

<footer>

<h3>Grupo Salud Integral Ayacucho</h3>

<p>
Atención integral para toda la familia
</p>

</footer>

<a class="whatsapp"
href="https://wa.me/5493517692619"
target="_blank">
💬
</a>

</body>
</html>
