<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>E-Commerces</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
</head>

<body>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#" style="font-weight: 800; color: darkgreen;">E-Commerce</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Blog</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Our Product
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Clothes</a></li>
              <li><a class="dropdown-item" href="#">Watches</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">All etc Fashion Item</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true">Sign In</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <div id="carouselExampleIndicators" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./pexels-photo-298863 mens or watches.jpeg" class="d-block w-100" alt="..." style=" width:300px; height: 500px;">
      </div>
      <div class="carousel-item">
        <img src="./download watch 2.jfif" class="d-block w-100" alt="..." style=" width:300px; height: 500px;">
      </div>
      <div class="carousel-item">
        <img src="./Shoes.webp" class="d-block w-100" alt="..." style=" width:300px; height: 500px;">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
      data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
      data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <div style=" display: flex; align-items: center; justify-content: space-around; margin-top: 20px;">
    <div class="card" style="width: 18rem;">
      <img src="./photo-1617689563472-c66428e83d17 shoes save.avif" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Shoes</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Buy Now</a>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./c42af627abc222376be52d4512e26ce9 save img.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Watch</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Buy Now</a>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./images (1).jfif" class="card-img-top" alt="..." style="width: 285px; height: 180px;">
      <div class="card-body">
        <h5 class="card-title">T-Shirts</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Buy Now</a>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./images (2).jfif" class="card-img-top" alt="..." style="width: 285px; height: 180px;">
      <div class="card-body">
        <h5 class="card-title">Shirts</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Buy Now</a>
      </div>
    </div>
  </div>
  <div
    style="display: grid; grid-template-columns: repeat(4,300px);  margin-top: 30px;  align-items: center; justify-content: space-evenly; height: 1000px; background-color: aliceblue">
    <div class="card" style="width: 18rem;">
      <img src="./download imges 345.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 30$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./download shhhhhh 125.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 40$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./images (3).jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 60$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./download imges 345.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 80$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./download imges 345.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 90$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./download imges 345.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 20$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./download imges 345.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 100$ Only</h2>
        </p>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img src="./download imges 345.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text">
        <h2>Price= 30$ Only</h2>
        </p>
      </div>
    </div>
  </div>
  <div style="height: 100px; display: flex; align-items: center; justify-content: space-evenly;">
    <span>&copy; copyright 2024</span>
    <span>Terms & Condition</span>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
    crossorigin="anonymous"></script>
</body>

</html>
