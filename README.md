<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LH Games</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">

  <link rel="stylesheet" href="css/estilo.css">



</head>

<body>
  <header>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="index.html"><img src="img/logo.png" alt=""></a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Promoções</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Console</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Jogos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="login.html">>>Login<<</a>
            </li>           
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="O que deseja buscar?" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Buscar</button>
          </form>
        </div>
      </div>
    </nav>
  </header>

  <main>



    <section id="section-banners" class="container-fluid">

      <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/banner1.PNG" class="d-block w-100" alt="Venha compra na nossa Loja!!!">
          </div>
          <div class="carousel-item">
            <img src="img/banner2.PNG" class="d-block w-100" alt="Promoções de Produto">
          </div>
          <div class="carousel-item">
            <img src="img/banner3.PNG" class="d-block w-100" alt="Várias Novidade de Produtos">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>  

    </section>
    <section id="section-vendidos" class="container-fluid">

      <h2>OS MAIS VENDIDOS</h2>

      <div class="card-group">
        <div class="card" style="width: 18rem;">
          <img src="img/jogo1.PNG" class="card-img-top" alt="Jogo de Aventura">
          <div class="card-body">
            <h5 class="card-title">jogo 1</h5>
            <p class="card-text">Jogo do Ano.</p>
            <p class="preco">R$ 190,00</p>
            <a class="btn btn-primary" href="" role="button">Comprar</a>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="img/jogo2.PNG" class="card-img-top" alt="Jogo de Corrida">
          <div class="card-body">
            <h5 class="card-title">jogo 2</h5>
            <p class="card-text">Jogo To de Linha.</p>
            <p class="preco">R$ 290,00</p>
            <a class="btn btn-primary" href="" role="button">Comprar</a>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="img/jogo3.PNG" class="card-img-top" alt="Melhor de Todos">
          <div class="card-body">
            <h5 class="card-title">jogo 3</h5>
            <p class="card-text">Melhor de Todos.</p>
            <p class="preco">R$ 150,00</p>
            <a class="btn btn-primary" href="" role="button">Comprar</a>
          </div>
        </div>
      </div>
    </section>


  </main>

  <footer>
    <p>Desenvolvido por Hugo Mattos</p>
  </footer>

  <button id="voltar-topo" type="button" class="btn btn-outline-primary" onclick="topo()">&uarr; Voltar ao topo</button>
  <script src="js/script.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3"
    crossorigin="anonymous"></script>

</body>

</html>
