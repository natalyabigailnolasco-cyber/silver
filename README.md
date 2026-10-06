<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MI MUNDO NATALY</title>
  <style>
    body {
      margin: 0;
    }

    .header {
      padding: 100,0px;
      background-color: hwb(340 93% 5%);
      text-align: center  ;
    }

    /* estilo parar la base del menu */
    .topnav {
      overflow: hidden;
      background-color: #b87a29;
    }

    /* Enlaces del menu */
    .topnav a {
      float: left;
      display: block;
      color: #f58ca3;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }

    /* Animacion para el menu */
    .topnav a:hover {
      background-color: #ddd;
      color: rgb(241, 89, 89)
    }

    /* Estilo para columnas */
    .row__column {
      float: left;
      padding: 15px;
    }

    .row__column.side {
      width: 15%;
    }

    .row__column.middle {
      width: 60%;
    }

    /* Contenido deje de ser flotante */
    .row::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Plantilla responsiva */
    @media screen and (max-width: 600px) {
      .row__column {
        width: 100%;
      }
    }

    /* Pie de pagina */
    .footer {
      background-color: #f1f1f1;
      padding: 10px;
      text-align: center;
	  
    }
	
	<link re="stylesheet" type="text/css" href="css/estilo.css" /> 
	
  </style>
</head>

<body>
  <!-- Definimos el area del encabezado -->
  <div class="header">
      <h1> 🤎CHOCOLATE DE CANELA 🤎</h1>
  </div>

  <!-- Crear el menu -->
  <div class="topnav">
    <a href="https://www.mined.gob.sv/" >VIVE</a>
	        <!--p align="rigth">MINED -->
    <a href="#">DULCEMENTE</a>
    <a href="#">LA VIDA</a>
	<a href="https://www.nintendo.com/us/">NATALYCHASHTE</a>
    <a href=""></a>
  </div>
  <!-- cuerpo de la pagina -->
  <div class="row">`
    <div class="row__column side">
      <h2> LOS MEJORES CHOCOLATES </h2>
      <p> Los mejores chocolates los encuentras aqui.</p>
    </div>
    <div class="row__column middle">
      <h2> DE CANELA </h2>
      <p> wooo que dulzura</p>
    </div>
    <div class="row__column side">
      <h2>chocolates</h2>
      <p> Que delicia.</p>
    </div>
  </div>
  <!-- inicio del piede de pagina -->
  <div class="footer">
   <marquee> <p> <h3> CON COCO🥥,ALMENDRAS🌰 Y FRESAS🍓</h3> </p></marquee>
  </div>
  <p>
  
  <div class="footer">
    <p> <h3>DULZURA EN CADA BOCADO 😋</h3> </p>
  </div>
  </p>
 <p>  <div class="footer">
   <MARQUEE> <p>  <h3>  💲LOS PRECIOS SON DE, $3 Y $4 💲 </h3> </p>
  </div>
  </p></MARQUEE>


    <p>
  
  <div class="footer">
    <p> <h3> 🤎 DISFRUTA CADA MOMENTO CON TUS CHOCOLATES FAVORITOS 🤎 </h3> </p>
  </div>
  </p>
   
  
  <audio controls> <source src="lapaz.mp3" type="audio/mp3"> Tu navegador no soporta audio HTML5. </audio>
 
  <marquee> <img src="fresas.jpg" w idth="400" height="200"/> </marquee>
  <marquee behavior="alternate"> <img src="foto de chamoyada.png" width="400" height="200"  onmouseOver="this.src='nip2.jpg'" onmouseOut= "this.src='Cari2.png'"/> </marquee>

     <video width="600" height="400" controls>
    <source src="pp.mp4" type="video/mp4">
       </video>
	   
	    
	   
	   
    
	<a href="Base Access China.html"> Registros  </a> <br> 
	
	<A HREF="index.html">  A hoja 2  </A> <br>
    <A HREF="iindex.html"> A hoja 3 </A>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Registro de Visitantes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      padding: 20px;
    }
    .formulario {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      max-width: 500px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .formulario h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .formulario label {
      display: block;
      margin-top: 10px;
    }
    .formulario input, .formulario textarea, .formulario select {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .formulario button {
      margin-top: 20px;
      width: 100%;
      padding: 10px;
      background-color: #007BFF;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .formulario button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <!--<div class="formulario">
    <h2>Registro de Visitantes</h2>
    <form action="procesar_registro.php" method="POST">
      <label for="nombre">Nombre completo:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="correo">Correo electrónico:</label>
      <input type="email" id="correo" name="correo" required>

      <label for="motivo">Motivo de la visita:</label>
      <textarea id="motivo" name="motivo" rows="3" required></textarea>

      <label for="fecha">Fecha de entrada:</label>
      <input type="date" id="fecha" name="fecha" required>

      <label for="hora">Hora de entrada:</label>
      <input type="time" id="hora" name="hora" required>

      <label for="identificacion">Número de identificación (DUI, carnet, etc.):</label>
      <input type="text" id="identificacion" name="identificacion">

      <button type="submit">Registrar</button>
    </form>
  </div> -->

<!--<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf6LXQ_qTlCHSNC-ZgxwdEln37_t5v2Hh6ocDeD2i2wPafUCA/viewform?embedded=true" width="640" height="568" frameborder="0" marginheight="0" marginwidth="0">Cargando…</iframe>-->

https://docs.google.com/spreadsheets/d/13HsCcHAgIrKN511fNy1tgMPfpdHYnRiSEOrYHAERCoE/edit?usp=sharing

</body>
</html>
    

