<html>
 <head><title>Mathématiques</title>
    <meta charset="utf-8"/>
    <link href="style.css" rel="stylesheet" type="text/css"/>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
 </head>
 <body>
 <center><p id="para2">Mathématiques</p></center>
 <p id="para3">Sur ce site, vous trouverez les cours de mathématiques, qui peuvent vous servir. En particulier pour ceux qui se préparent au Baccalauréat ou Brevet</p>
 <br>
<div class="w3-container">
  <h2>Mathématiques </h2>
  <p>Choisissez une classe</p>
</div>

<div class="w3-bar w3-black">
  <button class="w3-bar-item w3-button" onclick="openCity('Seconde')">Seconde</button>
  <button class="w3-bar-item w3-button" onclick="openCity('Première')">Première G</button>
  <button class="w3-bar-item w3-button" onclick="openCity('Terminale')">Terminale G</button>
  <button class="w3-bar-item w3-button" onclick="openCity('Français')">Français Première-BAC</button>
</div>
<!--
<div id="Seconde" class="w3-container city">
    <h2>-</h2>
    <p>--</p> 
</div>
<div id="Première" class="w3-container city" style="display:none">
  <h2>-</h2>
  <p>--</p> 
</div>-->

<div id="Terminale" class="w3-container city" style="display:none">
 <p id="para1">Equations différentielles</p>
    <ul>
      <li><a href="mat/equadif.pdf" dowload=""><h2>Cours-Equations differentielles</h2></a></li>
      <li><a href="TD.pdf" dowload=""><h2>TD-Equations differentielles</h2></a></li>
      <li><a href="TD-correction.pdf" dowload=""><h2>Correction-Equations differentielles</h2></a></li>
   </ul>
  <p></p>
</div>

<div id="Français" class="w3-container city" style="display:none">
  <center><p id="para1">Français- Première - BAC</p></center>
  <p id="para4">- Programme officiel- Français pour  2024-2025</p id="para4">
    <ul>
        <li><a href="fr/2024-2025-G.pdf" dowload=""><h2>Les œuvres au programme de Première Générale</h2></a></li>
        <li><a href="fr/2024-2025-T.pdf" dowload=""><h2>Les œuvres au programme de Première Technologique</h2></a></li> 
    </ul>
    <p id="para4">Arthur RIMBAUD, <i>Cahier de Douai</i></p id="para4">
    <br><a href="fr/Rimbaud-Cahier_de_Douai.pdf" dowload=""><h2>Présentation de l'œuvre-1</h2></a>
    <p id="para4">Sujets de dissertation</p id="para4">
    <br><a href="fr/Sujet_de_dissertation.pdf" dowload=""><h2>Dissertation</h2></a>
</div>



 
<script>
function openCity(cityName) {
  var i;
  var x = document.getElementsByClassName("city");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  document.getElementById(cityName).style.display = "block";  
}
</script>

</body>
</html>