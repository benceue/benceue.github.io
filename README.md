# 
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="=device-width, initial-scale=1">

  <title>HTML</title>
  
  <!-- HTML" -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>
 </h1>IgamMc</h1>
   
  <h1>Gondolkodtál már azon, hogy...
Milyen érzés lehet Magyarország legnagyobb Minecraft szerverén játszani?
Légy te is részese az évek óta rendíthetetlen, élményekkel teli közösségnek!</h1>
  <script src="main.js"></script>
  
  
</body>
</html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="=device-width, initial-scale=1">

  <title>HTML</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <script src="main.js"></script>
  
</body>
</html>
<!DOCTYPE html>
<html lang="hu">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FyreMC Menü</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #000;
      color: white;
    }

    /* Menü gomb */
    .menu-button {
      position: fixed;
      top: 20px;
      right: 20px;
      z-index: 1001;
      font-size: 30px;
      background: none;
      border: none;
      color: white;
      cursor: pointer;
    }

    /* Menü háttér */
    .menu {
      position: fixed;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background-color: rgba(140, 131, 131, 0.95);
      backdrop-filter: blur(5px);
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      z-index: 1000;
    }

    .menu.active {
      display: flex;
    }

    .menu a {
      color: white;
      font-size: 2em;
      text-decoration: none;
      margin: 15px 0;
    }

    .menu a.register {
      color: orange;
    }

    .menu .button {
      background: linear-gradient(to right, #f57c00, #69A698);
      color: white;
      padding: 15px 30px;
      font-weight: bold;
      border-radius: 10px;
      text-transform: uppercase;
      box-shadow: 0 4px 6px rgba(0,0,0,0.3);
      margin-top: 20px;
    }

    .menu-header {
      position: absolute;
      top: 20px;
      left: 20px;
      right: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .menu-logo {
      height: 50px;
    }

    .close-button {
      font-size: 30px;
      color: white;
      cursor: pointer;
    }
  </style>
</head>
<body>

<!-- Menü nyitó gomb -->
<button class="menu-button" onclick="toggleMenu()">☰</button>

<!-- Menü -->
<div class="menu" id="menu">
  <div class="menu-header">
    <img src="fyremc-logo.png" alt="Logo" class="menu-logo">
    <span class="close-button" onclick="toggleMenu()">✖</span>
  </div>

  <a href="#">Főoldal</a>
  <a href="#">Segítség</a>
  <a href="spera.html">Bejelentkezes</a>
  <a href="sperma.html" class="register">Regisztráció</a>
  <a href="letoltes.html" class="button">Letöltés</a>
</div>

<script>
  function toggleMenu() {
    document.getElementById("menu").classList.toggle("active");
  }
</script>

</body>
</html>


