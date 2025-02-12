<html>
 <head><title>Mathématiques</title>
    <meta charset="utf-8"/>
    <link href="style.css" rel="stylesheet" type="text/css"/>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
 </head>
 <body>
 <center><h1 id="h1">Mathématiques</h1></center>
 <p id="para3">Sur ce site, vous trouverez les cours de mathématiques, qui peuvent vous servir. En particulier pour ceux qui se préparent au Baccalauréat ou Brevet</p>
 <br>
<div class="w3-container">
  <p>Choisissez une classe</p>
</div>

<div class="w3-bar w3-black">
  <!--<button class="w3-bar-item w3-button" onclick="openCity('Six')">Sixième</button>
<button class="w3-bar-item w3-button" onclick="openCity('Cinq')">Cinquième</button>
<button class="w3-bar-item w3-button" onclick="openCity('Quatre')">Quatrième</button>
<button class="w3-bar-item w3-button" onclick="openCity('Trois')">Troisième</button>
  <button class="w3-bar-item w3-button" onclick="openCity('Seconde')">Seconde</button>-->
  <button class="w3-bar-item w3-button" onclick="openCity('Première')">Première G</button>
  <button class="w3-bar-item w3-button" onclick="openCity('Terminale')">Terminale G</button>
  <button class="w3-bar-item w3-button" onclick="openCity('Français')">Français Première-BAC</button>
</div>
<!--
<div id="Six" class="w3-container city">
    <p id="para2">-</p>
    <p>--</p> 
</div>
<div id="Cinq" class="w3-container city">
    <p id="para2">-</p>
    <p>--</p> 
</div>
<div id="Quatre" class="w3-container city">
    <p id="para2">-</p>
    <p>--</p> 
</div>
<div id="Tois" class="w3-container city">
    <p id="para2">-</p>
    <p>--</p> 
</div>
<div id="Seconde" class="w3-container city">
    <p id="para2">-</p>
    <p>--</p> 
</div>
<div id="Première" class="w3-container city" style="display:none">
  <p id="para2">-</p>
  <p>--</p> 
</div>-->

<div id="Terminale" class="w3-container city" style="display:none">
 <p id="para1">Terminale Générale</p>
 <p id="para6">Equations différentielles</p>
    <ul>
      <li><a href="mat/equadif.pdf" dowload=""><p id="para4">Cours-Equations differentielles</p></a></li>
      <li><a href="TD.pdf" dowload=""><p id="para4">TD-Equations differentielles</p></a></li>
      <li><a href="TD-correction.pdf" dowload=""><p id="para4">Correction-Equations differentielles</p></a></li>
   </ul>
  <p></p>
</div>

<div id="Français" class="w3-container city" style="display:none">
  <center><p id="para1">Français- Première - BAC</p></center>
  <p id="para2">- Programme officiel- Français pour  2024-2025</p>
    <ul>
        <li><a href="fr/2024-2025-G.pdf" dowload=""><p id="para4">Les œuvres au programme de Première Générale</p></a></li>
        <li><p id="para4"><a href="fr/2024-2025-T.pdf" dowload="">Les œuvres au programme de Première Technologique</a></p></li> 
    </ul>
    <p id="para2">Arthur RIMBAUD, <i>Cahier de Douai</i></p>
        <ul>
            <li><a href="fr/Rimbaud-Cahier_de_Douai.pdf" dowload=""><p id="para4">Présentation de l'œuvre-1</p></a></li>
        </ul>    
    <p id="para2">Sujets de dissertation</p>
    <br><a href="fr/Sujet_de_dissertation.pdf" dowload=""><p id="para4">Dissertation</p></a>
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
