<head>
  <title>Cycle Bikes</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <link href="style.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha384-A7FZj7v+d/sdmMqp/nOQwliLvUsJfDHW+k9Omg/a/EheAdgtzNs3hpfag6Ed950n" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" integrity="sha384-DztdAPBWPRXSA/3eYEEUWrWCy7G5KFbe8fFjk5JAIxUYHKkDx6Qin1DkWx51bBrb" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>
</head>
<header>
  <div class="jumbotron text-center" style="background-color: #F5F5F5;">
    <h1 id="home" style="color: #424242">Cycles Bikes</h1>
    <p>Bicicletas sob encomenda</p>
    <p class="text-center"></p>
  </div>
</header>
<nav>
  <ul class="nav justify-content-center">
    <li class="nav-item">
      <a class="nav-link" href="/" style="color: #424242;">Home</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="/sobre" style="color: #424242;">Sobre</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="/produtos" style="color: #424242;">Produtos</a>
    </li>
  </ul>
</nav>

<slot />

<footer id="contato">
    <h2>Contato</h2>
    <p>Telefone: (XX) 99999-9999 <br> Email: contato@cyclesbikes.com</p>
    <img src="https://cdn.pixabay.com/photo/2015/01/13/13/20/guy-598180__340.jpg" alt="homem-com-bicicleta">
</footer>

<style>
    * {
  text-align: center;
}
.carousel-inner img {
  margin: auto;
}
footer {
  color: #424242;
  background-color: #f5f5f5;
}
footer img {
  border-radius: 50%;
  width: 15%;
}
</style>