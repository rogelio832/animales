# animales<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ANIMAL WORLD</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Poppins', sans-serif;
}

body{
background:linear-gradient(135deg,#041b12,#0b2e1f,#123524);
color:white;
overflow-x:hidden;
}

/* Fondo animado */

body::before{
content:'';
position:fixed;
width:200%;
height:200%;
background:
radial-gradient(circle,#00ff8844 1px, transparent 1px);
background-size:40px 40px;
animation:fondo 20s linear infinite;
z-index:-1;
}

@keyframes fondo{
0%{
transform:translate(0,0);
}
100%{
transform:translate(-120px,-120px);
}
}

/* HEADER */

header{
text-align:center;
padding:50px 20px;
border-bottom:3px solid #00ff88;
box-shadow:0 0 20px #00ff88;
}

header h1{
font-size:60px;
color:#00ff88;
text-shadow:0 0 20px #00ff88;
}

header p{
margin-top:15px;
color:#ccc;
font-size:18px;
}

/* MENU */

nav{
display:flex;
justify-content:center;
gap:20px;
padding:25px;
flex-wrap:wrap;
}

nav a{
text-decoration:none;
color:white;
padding:12px 25px;
border:2px solid #00ff88;
border-radius:15px;
transition:.3s;
box-shadow:0 0 10px #00ff88;
}

nav a:hover{
background:#00ff88;
color:black;
transform:scale(1.1);
}

/* SECCIONES */

.seccion{
padding:70px 25px;
max-width:1200px;
margin:auto;
}

.card{
background:#102018;
border:2px solid #00ff88;
border-radius:25px;
overflow:hidden;
margin-bottom:40px;
box-shadow:0 0 20px #00ff8866;
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 35px #00ff88;
}

.card img{
width:100%;
height:350px;
object-fit:cover;
}

.card-content{
padding:30px;
}

.card h2{
color:#00ff88;
margin-bottom:20px;
font-size:35px;
}

.card p{
line-height:1.9;
color:#ddd;
font-size:16px;
}

/* BOTONES */

.boton{
display:inline-block;
margin-top:25px;
padding:14px 25px;
background:#00ff88;
color:black;
text-decoration:none;
font-weight:bold;
border-radius:15px;
transition:.3s;
}

.boton:hover{
background:#00ccff;
color:white;
box-shadow:0 0 20px #00ccff;
}

/* TABLA */

table{
width:100%;
border-collapse:collapse;
margin-top:20px;
}

table th,
table td{
border:1px solid #00ff88;
padding:15px;
text-align:center;
}

table th{
background:#00ff88;
color:black;
}

/* FOOTER */

footer{
text-align:center;
padding:35px;
border-top:3px solid #00ff88;
color:#aaa;
margin-top:40px;
}

</style>
</head>

<body>

<header>

<h1>🐾 ANIMAL WORLD 🐾</h1>

<p>
Descubre animales increíbles del planeta 🌎
</p>

</header>

<nav>

<a href="#mamiferos">Mamíferos</a>
<a href="#aves">Aves</a>
<a href="#marinos">Marinos</a>
<a href="#salvajes">Salvajes</a>
<a href="#curiosidades">Curiosidades</a>

</nav>

<!-- MAMIFEROS -->

<section class="seccion" id="mamiferos">

<div class="card">

<img src="https://images.unsplash.com/photo-1546182990-dffeafbe841d">

<div class="card-content">

<h2>🦁 Mamíferos</h2>

<p>
Los mamíferos son animales que alimentan a sus crías con leche.
Existen mamíferos terrestres, acuáticos y voladores.
</p>

<p>
Ejemplos:
leones, perros, gatos, elefantes y delfines.
</p>

<a class="boton" href="#aves">Ver aves</a>

</div>
</div>

</section>

<!-- AVES -->

<section class="seccion" id="aves">

<div class="card">

<img src="https://images.unsplash.com/photo-1444464666168-49d633b86797">

<div class="card-content">

<h2>🦅 Aves</h2>

<p>
Las aves tienen plumas, pico y la mayoría puede volar.
Algunas aves migran miles de kilómetros cada año.
</p>

<table>

<tr>
<th>Ave</th>
<th>Velocidad</th>
</tr>

<tr>
<td>Águila</td>
<td>160 km/h</td>
</tr>

<tr>
<td>Halcón</td>
<td>320 km/h</td>
</tr>

<tr>
<td>Loro</td>
<td>50 km/h</td>
</tr>

</table>

</div>
</div>

</section>

<!-- MARINOS -->

<section class="seccion" id="marinos">

<div class="card">

<img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5">

<div class="card-content">

<h2>🐬 Animales marinos</h2>

<p>
Los océanos están llenos de vida.
Hay tiburones, ballenas, delfines, pulpos y miles de especies increíbles.
</p>

<p>
La ballena azul es el animal más grande del planeta 🌎
</p>

<a class="boton" href="#salvajes">Continuar</a>

</div>
</div>

</section>

<!-- SALVAJES -->

<section class="seccion" id="salvajes">

<div class="card">

<img src="https://images.unsplash.com/photo-1474511320723-9a56873867b5">

<div class="card-content">

<h2>🐯 Animales salvajes</h2>

<p>
Los animales salvajes viven en libertad en selvas, bosques y sabanas.
Muchos están en peligro de extinción debido a la contaminación y caza ilegal.
</p>

<p>
Es importante proteger la naturaleza y respetar a los animales.
</p>

</div>
</div>

</section>

<!-- CURIOSIDADES -->

<section class="seccion" id="curiosidades">

<div class="card">

<img src="https://images.unsplash.com/photo-1501706362039-c6e08b2f2074">

<div class="card-content">

<h2>🤯 Curiosidades animales</h2>

<p>
🐙 Los pulpos tienen 3 corazones.<br><br>

🦒 Las jirafas solo duermen alrededor de 2 horas al día.<br><br>

🐘 Los elefantes pueden reconocer su reflejo en un espejo.<br><br>

🐧 Los pingüinos le dan piedras a su pareja como regalo.
</p>

<a class="boton" href="#mamiferos">Volver arriba</a>

</div>
</div>

</section>

<footer>

<p>
© 2026 Animal World | Página creada para amantes de los animales 🐾
</p>

</footer>

</body>
</html>