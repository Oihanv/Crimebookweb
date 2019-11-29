<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" type="text/css" href="estilos.css">
  <title>Crimebook</title>
</head>
<body>
<div style="margin-top:8vh">

<br><br>
<p id="bienvenidos" >BIENVENIDOS AL</p>
<p id="crimebook"> CRIMEBOOK</p>

<!-- Boton que es -->

<button onclick="document.getElementById('id01').style.display='block'" style="width:auto; margin-top:2vh" class="botonquees"><span>¿QUÉ ES?</span></button>

<div id="id01" class="modal">

  <form class="modal-content animate" action="/action_page.php" method="post">


    <div class="container">
      <div class="letradefault">

        <h2 id="queescrimebook" > ¿QUE ES? </h2>
        <hr id="linea">
        <div id="explicacioncrimebook">

        <p>texto</p>
        <p>texto</p>
        <p>texto</p>
        <p>texto</p>
        <p>texto</p>

        </div>
        <hr id="linea">
      </div>
    </div>
  </form>
</div>
<script>
// Get the modal
var modal = document.getElementById('id01');

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script>

<!-- ------------- -->
</div>

<br><br><br><br>
<div class="logo">
  <a href="pagina_2.html" title="home page" target="_blank">
      <img src="img/logo.png" style="width:100%"></a>
</div>
<button class="botonadmin"><span>ADMIN </span></button>


</body>
</html>
