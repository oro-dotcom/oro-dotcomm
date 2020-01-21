# oro-dotcomm
<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<body id="myPage">

<!-- Sidebar on click -->
<nav class="w3-sidebar w3-bar-block w3-white w3-card w3-animate-left w3-xxlarge" style="display:none;z-index:2" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-display-topright w3-text-teal">
    <i class="fa fa-remove"></i>
  </a>
  <a href="#home" class="w3-bar-item w3-button">Home</a>
  <a href="#team" class="w3-bar-item w3-button">Comienza</a>
  <a href="#work" class="w3-bar-item w3-button">Leyendas</a>
  <a href="#pricing" class="w3-bar-item w3-button">Tienda</a>
  <a href="#contact" class="w3-bar-item w3-button">Síguenos</a>
</nav>

<!-- Navbar -->
<div class="w3-top">
 <div class="w3-bar w3-theme-d2 w3-left-align">
  <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-hover-white w3-theme-d2" href="javascript:void(0);" onclick="openNav()"><i class="fa fa-bars"></i></a>
  <a href="#home" class="w3-bar-item w3-button w3-teal"><i class="fa fa-home w3-margin-right"></i>Inicio</a>
  <a href="#team" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Variedades</a>
  <a href="#work" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Leyendas </a>
  <a href="#pricing" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Tienda</a>
  <a href="#contact" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Contacto</a>
    <div class="w3-dropdown-hover w3-hide-small">
    <button class="w3-button" title="Notifications">Aprende NBA <i class="fa fa-caret-down"></i></button>     
    <div class="w3-dropdown-content w3-card-4 w3-bar-block">
      <a href="paginaweb 2.html" class="w3-bar-item w3-button">Estadios</a>
      <a href="paginaweb 3.html" class="w3-bar-item w3-button"> NBA 2K20</a>
  
    </div>
  </div>
  <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right w3-hover-teal" title="Search"><i class="fa fa-search"></i></a>
 </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-theme-d2 w3-hide w3-hide-large w3-hide-medium">
    <a href="#team" class="w3-bar-item w3-button">Team</a>
    <a href="#work" class="w3-bar-item w3-button">Work</a>
    <a href="#pricing" class="w3-bar-item w3-button">Price</a>
    <a href="#contact" class="w3-bar-item w3-button">Contact</a>
    <a href="#" class="w3-bar-item w3-button">Search</a>
  </div>
</div>

<!-- Image Header -->
<div class="w3-display-container w3-animate-opacity">
  <img src="imagenes/fondo.jpg" alt="boat" style="width:100%;min-height:350px;max-height:600px;">
  <div class="w3-container w3-display-bottomleft w3-margin-bottom">  
    <button onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-xlarge w3-theme w3-hover-teal" title="Go To W3.CSS">National Basketball Association</button>
  </div>
</div>

<!-- Modal -->
<div id="id01" class="w3-modal">
  <div class="w3-modal-content w3-card-4 w3-animate-top">
    <header class="w3-container w3-teal w3-display-container"> 
      <span onclick="document.getElementById('id01').style.display='none'" class="w3-button w3-teal w3-display-topright"><i class="fa fa-remove"></i></span>
      <h4>Oh snap! We just showed you a modal..</h4>
      <h5>Because we can <i class="fa fa-smile-o"></i></h5>
    </header>
    <div class="w3-container">
      <p>Cool huh? Ok, enough teasing around..</p>
      <p>Go to our <a class="w3-text-teal" href="/w3css/default.asp">W3.CSS Tutorial</a> to learn more!</p>
    </div>
    <footer class="w3-container w3-teal">
      <p>Modal footer</p>
    </footer>
  </div>
</div>

<!-- Team Container -->
<div class="w3-container w3-padding-64 w3-center" id="team">
<h1>Comienza a entender la NBA</h1>
<h3><p>El baloncesto es un juego de por vida. Continúas aprendiendo del juego día tras día y, a lo largo del camino, te vuelves mejor. – Scottie Pippen</p></h3>

<div class="w3-row"><br>

<div class="w3-quarter">
  <img src="imagenes/2k.jfif" alt="Boss" style="width:45%" class="w3-circle w3-hover-opacity">
  <h3>NBA 2K</h3>
  <p>El videojuego mas popular de baloncesto.</p>
</div>

<div class="w3-quarter">
 <img src="imagenes/doncic.jfif" alt="Boss" style="width:45%" class="w3-circle w3-hover-opacity">
  <h3>Equipos afiliados</h3>
  <p> Promesas hoy leyendas mañana.</p>
</div>

<div class="w3-quarter">
<img src="imagenes/estadio.jfif" alt="Boss" style="width:45%" class="w3-circle w3-hover-opacity">

  <h3>Equipos de ciudades.</h3>
  <p>Cada equipo de la NBA tiene su sede en una ciudad.</p>
</div>

<div class="w3-quarter">
  <img src="imagenes/españa.jfif" alt="Boss" style="width:45%" class="w3-circle w3-hover-opacity">
  <h3>Ligas mundiales</h3>
  <p>Este deporte se practica al rededor del mundo,los mejores,de la NBA</p>
</div>

</div>
</div>

<!-- Work Row -->
<div class="w3-row-padding w3-padding-64 w3-theme-l1" id="work">

<div class="w3-quarter">
<h2>Leyendas de la NBA</h2>
<p>¡Bienvenido! ¡Si quieres conseguir la última información de la NBA, sus equipos y jugadores sigue nuestras redes sociales ¡en español! La mejor información sobre la NBA, la liga estadounidense de baloncesto profesional Sigue toda la información de la NBA.</p>
</div>

<div class="w3-quarter">
<div class="w3-card w3-white">
  <img src="imagenes/jordan.jpg" alt="Snow" style="width:100%">
  <div class="w3-container">
  <h3>Michael Jordan</h3>
  <h4>EE.UU</h4>
  <p> Está considerado por la mayoría de aficionados y especialistas como el mejor jugador de baloncesto de todos los tiempos.</p>
  </div>
  </div>
</div>

<div class="w3-quarter">
<div class="w3-card w3-white">
  <img src="imagenes/pau.jpg" alt="Lights" style="width:100%">
  <div class="w3-container">
  <h3>Pau Gasol</h3>
  <h4>España</h4>
  <p>Se convirtió en el segundo español en jugar en la NBA tras Fernando Martín, siendo el primero en ser elegido para jugar un All-Star Game de la NBA, en clasificarse para los playoffs, y en conseguir el campeonato de la NBA</p>
  </div>
  </div>
</div>

<div class="w3-quarter">
<div class="w3-card w3-white">
  <img src="imagenes/kobe.jfif" alt="Mountains" style="width:100%">
  <div class="w3-container">
  <h3>Kobe Bryant</h3>
  <h4>EE.UU</h4>
  <p>Tercer máximo anotador en la historia de la liga,disputó veinte temporadas en la NBA, todas ellas en Los Angeles Lakers, desde 1996 hasta 2016.</p>
  </div>
  </div>
</div>

</div>

<!-- Container -->
<div class="w3-container" style="position:relative">
  <a onclick="w3_open()" class="w3-button w3-xlarge w3-circle w3-teal"
  style="position:absolute;top:-28px;right:24px">+</a>
</div>

<!-- Pricing Row -->
<div class="w3-row-padding w3-center w3-padding-64" id="pricing">
    <h2> Algunos artículos de la tienda NBA</h2>
    <p>La tienda de la NBA a tu disposición.</p><br>
    <div class="w3-third w3-margin-bottom">
      <ul class="w3-ul w3-border w3-hover-shadow">
        <li class="w3-theme">
          <p class="w3-xlarge">Entrenamiento</p>
        </li>
        <li class="w3-padding-16"><b>SPURS</b> San Antonio</li>
        <li class="w3-padding-16"><b>Camiseta</b>  Manga corta</li>
        <li class="w3-padding-16"><b>Logo</b> Spurs</li>
        <li class="w3-padding-16"><b>Garantia</b> Calidad</li>
        <li class="w3-padding-16">
         
        </li>
        <li class="w3-theme-l5 w3-padding-24">
          <button class="w3-button w3-teal w3-padding-large"><i class="fa fa-check"></i>  Observa en tienda oficial</button>
        </li>
      </ul>
    </div>

    <div class="w3-third w3-margin-bottom">
      <ul class="w3-ul w3-border w3-hover-shadow">
        <li class="w3-theme-l2">
          <p class="w3-xlarge">Juego</p>
        </li>
        <li class="w3-padding-16"><b>WARRIORS</b> Golden State</li>
        <li class="w3-padding-16"><b>Camiseta</b> Sin mangas</li>
        <li class="w3-padding-16"><b>Stephen Curry</b> </li>
        <li class="w3-padding-16"><b>Garantía </b> Calidad</li>
        <li class="w3-padding-16">
         
        </li>
        <li class="w3-theme-l5 w3-padding-24">
          <button class="w3-button w3-teal w3-padding-large"><i class="fa fa-check"></i> Observa en tienda oficial</button>
        </li>
      </ul>
    </div>

    <div class="w3-third w3-margin-bottom">
      <ul class="w3-ul w3-border w3-hover-shadow">
        <li class="w3-theme">
          <p class="w3-xlarge">Históricas</p>
        </li>
        <li class="w3-padding-16"><b>Tim</b> Duncan</li>
        <li class="w3-padding-16"><b>1990</b> NBA finals</li>
        <li class="w3-padding-16"><b>Miami Final</b> </li>
        <li class="w3-padding-16"><b>Financiación</b> Gregg Popovich</li>
        <li class="w3-padding-16">
          
        </li>
        <li class="w3-theme-l5 w3-padding-24">
          <button class="w3-button w3-teal w3-padding-large"><i class="fa fa-check"></i>Observa en tienda oficial</button>
        </li>
      </ul>
    </div>
</div>

<!-- Contact Container -->
<div class="w3-container w3-padding-64 w3-theme-l5" id="contact">
  <div class="w3-row">
    <div class="w3-col m5">
    <div class="w3-padding-16"><span class="w3-xlarge w3-border-teal w3-bottombar">Contáctanos</span></div>
      <h3>Dirección</h3>
      <p>Cualquier pregunta o cualquier duda.</p>
      <p><i class="fa fa-map-marker w3-text-teal w3-xlarge"></i>  Chicago, EE.UU</p>
      <p><i class="fa fa-phone w3-text-teal w3-xlarge"></i>  +00 1515151515</p>
      <p><i class="fa fa-envelope-o w3-text-teal w3-xlarge"></i>  nbaenespañol@gmail.com</p>
    </div>
    <div class="w3-col m7">
      <form class="w3-container w3-card-4 w3-padding-16 w3-white" action="/action_page.php" target="_blank">
      <div class="w3-section">      
        <label>Nombre</label>
        <input class="w3-input" type="text" name="Name" required>
      </div>
      <div class="w3-section">      
        <label>Email</label>
        <input class="w3-input" type="text" name="Email" required>
      </div>
      <div class="w3-section">      
        <label>Mensaje</label>
        <input class="w3-input" type="text" name="Message" required>
      </div>  
      <input class="w3-check" type="checkbox" checked name="Like">
      <label>Me gusta!</label>
      <button type="submit" class="w3-button w3-right w3-theme">Enviar</button>
      </form>
    </div>
  </div>
</div>

<!-- Image of location/map -->
<img src="/w3images/map.jpg" class="w3-image w3-greyscale-min" style="width:100%;">

<!-- Footer -->
<footer class="w3-container w3-padding-32 w3-theme-d1 w3-center">
  <h4>Síguenos</h4>
  <a class="w3-button w3-large w3-teal" href="javascript:void(0)" title="Facebook"><i class="fa fa-facebook"></i></a>
  <a class="w3-button w3-large w3-teal" href="javascript:void(0)" title="Twitter"><i class="fa fa-twitter"></i></a>
  <a class="w3-button w3-large w3-teal" href="javascript:void(0)" title="Google +"><i class="fa fa-google-plus"></i></a>
  <a class="w3-button w3-large w3-teal" href="javascript:void(0)" title="Google +"><i class="fa fa-instagram"></i></a>
  <a class="w3-button w3-large w3-teal w3-hide-small" href="javascript:void(0)" title="Linkedin"><i class="fa fa-linkedin"></i></a>
  <p>Promocionado por <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>

  <div style="position:relative;bottom:100px;z-index:1;" class="w3-tooltip w3-right">
    <span class="w3-text w3-padding w3-teal w3-hide-small">Ir Arriba</span>   
    <a class="w3-button w3-theme" href="#myPage"><span class="w3-xlarge">
    <i class="fa fa-chevron-circle-up"></i></span></a>
  </div>
</footer>

<script>
// Script for side navigation
function w3_open() {
  var x = document.getElementById("mySidebar");
  x.style.width = "300px";
  x.style.paddingTop = "10%";
  x.style.display = "block";
}

// Close side navigation
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}

// Used to toggle the menu on smaller screens when clicking on the menu button
function openNav() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>

</body>
</html>
