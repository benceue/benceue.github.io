
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="=device-width, initial-scale=1">

  
  
  <!-- HTML" -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body
<!DOCTYPE html>
<html lang="hu">
<head>
  <meta charset="UTF-8">
  <title>Cookie értesítés</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .cookie-banner {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background-color: #2c2c2c;
      color: white;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
    }

    .cookie-banner p {
      margin: 0;
      font-size: 14px;
    }

    .cookie-banner button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      border-radius: 5px;
    }

    .cookie-banner button:hover {
      background-color: #45a049;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>

  <div id="cookieBanner" class="cookie-banner">
    <p>Ez a weboldal cookie-kat használ a jobb felhasználói élmény érdekében.</p>
    <button onclick="acceptCookies()">Elfogadom</button>
  </div>

  <script>
    function acceptCookies() {
      document.getElementById("cookieBanner").classList.add("hidden");
      localStorage.setItem("cookiesAccepted", "true");
    }

    window.onload = function () {
      if (localStorage.getItem("cookiesAccepted") === "true") {
        document.getElementById("cookieBanner").classList.add("hidden");
      }
    };
  </script>

</body>
</html>

  

  

</body>
</html>

  
  
  
  
  
  
  
  
  
<h1><em><marquee><u>Üdvözlünk></u></marquee></em></h1>
   
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
    <img src="https://i.postimg.cc/wMYB6w5t/IMG-0981.png" alt="Logo" class="menu-logo">
    <span class="close-button" onclick="toggleMenu()">✖</span>
  </div>

  <a href="Főoldal.html.html">Főoldal</a>
  <a href="Segítség.html">Segítség</a>
  <a href="bejelentkezes.html">Bejelentkezes</a>
  <a href="register.html" class="register">Regisztráció</a>
  <a href="letoltes.html" class="button">Letöltés</a>
</div>

<script>
  function toggleMenu() {
    document.getElementById("menu").classList.toggle("active");
  }
</script>

</body>



</html>

<h1><em><marquee><u>Igammc</u></u></marquee></em></h1>
