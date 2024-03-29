<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;400;900&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
  <!-- FontAwesome -->
  <script src="https://kit.fontawesome.com/afcb49ea32.js" crossorigin="anonymous"></script>

  <link rel="stylesheet" href="css/styles.css">
  
<body>



  <section class="colored-section" id="title">
    <div class="container-fluid">
      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="">tindog</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#footer">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#pricing">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
            </li>
          </ul>
        </div>
      </nav>
      <!-- Title -->
      <div class="row">

        <div class="col-lg-6">
          <h1>Meet new and interesting dogs nearby.</h1>
          <button class="btn btn-dark btn-lg download-button" type="button"><i class="fa-brands fa-apple"></i> Download</button>
          <button class="btn btn-outline-light btn-lg download-button" type="button"><i class="fa-brands fa-google-play"></i> Download</button>
        </div>
        <div class="col-lg-6 img-container">
          <img class="title-img" src="images/iphone6.png" alt="iphone-mockup">
        </div>

      </div>
    </div>
  </section>


  <!-- Features -->

  <section class="white-section" id="features">
    <div class="row">
      <div class="col-lg-4 feature-box">
        <i class="fa-solid fa-circle-check fa-4x icon-spcs"></i>

        <h3 class="headers">Easy to use.</h3>
        <p class="headers-text">So easy to use, even your dog could do it.</p>
      </div>

      <div class="col-lg-4 feature-box">
        <i class="fa-solid fa-bullseye fa-4x icon-spcs"></i>

        <h3 class="headers">Elite Clientele</h3>
        <p class="headers-text">We have all the dogs, the greatest dogs.</p>
      </div>

      <div class="col-lg-4 feature-box">
        <i class="fa-solid fa-heart fa-4x icon-spcs"></i>

        <h3 class="headers">Guaranteed to work.</h3>
        <p class="headers-text">Find the love of your dog's life or your money back.</p>
      </div>

    </div>
  </section>


  <!-- Testimonials -->

  <section class="colored-section" id="testimonials">

    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2 class="test-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="test-img" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item">
          <h2 class="test-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="test-img" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

  </section>


  <!-- Press -->

  <section class="colored-section" id="press">
    <img class="press-img" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-img" src="images/tnw.png" alt="tnw-logo">
    <img class="press-img" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-img" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section class="white-section" id="pricing">

    <h2 class="pricing-title">A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="row">
      <div class="col-lg-4 col-md-6">
        <div class="card style-card">
          <div class="card-header">
            <h3 class="pricing-title">Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2 class="pricing-title">Free</h2>
            <p><i class="fa-solid fa-bone"></i>  5 Matches Per Day</p>
            <p><i class="fa-solid fa-bone"></i>  10 Messages Per Day</p>
            <p><i class="fa-solid fa-bone"></i>  Unlimited App Usage</p>
            <button class="btn btn-outline-dark btn-lg" type="button">Sign Up</button>
          </div>
        </div>
      </div>


      <div class="col-lg-4 col-md-6">
        <div class="card style-card">
          <div class="card-header">
            <h3 class="pricing-title">Labrador</h3>
          </div>
          <div class="card-body">
            <h2 class="pricing-title">$49 / mo</h2>
            <p><i class="fa-solid fa-bone"></i>  Unlimited Matches</p>
            <p><i class="fa-solid fa-bone"></i>  Unlimited Messages</p>
            <p><i class="fa-solid fa-bone"></i>  Unlimited App Usage</p>
            <button class="btn btn-dark btn-lg" type="button">Sign Up</button>
          </div>
        </div>
      </div>


      <div class="col-lg-4">
        <div class="card style-card">
          <div class="card-header">
            <h3 class="pricing-title">Mastiff</h3>
          </div>
          <div class="card-body">
            <h2 class="pricing-title">$99 / mo</h2>
            <p><i class="fa-solid fa-bone"></i>  Pirority Listing</p>
            <p><i class="fa-solid fa-bone"></i>  Unlimited Matches</p>
            <p><i class="fa-solid fa-bone"></i>  Unlimited Messages</p>
            <p><i class="fa-solid fa-bone"></i>  Unlimited App Usage</p>
            <button class="btn btn-dark btn-lg" type="button">Sign Up</button>
          </div>
        </div>
      </div>
    </div>


  </section>


  <!-- Call to Action -->

  <section class="colored-section" id="cta">

    <h3 class="cta-text">Find the True Love of Your Dog's Life Today.</h3>
    <button class="btn btn-lg btn-secondary download-button-cta" type="button"><i class="fa-brands fa-apple"></i> Download</button>
    <button class="btn btn-lg btn-light download-button-cta" type="button"><i class="fa-brands fa-google-play"></i> Download</button>

  </section>


  <!-- Footer -->

  <footer class="white-section" id="footer">

    <i class="fa-brands fa-twitter icon-footer"></i>
    <i class="fa-brands fa-facebook-f icon-footer"></i>
    <i class="fa-brands fa-instagram icon-footer"></i>
    <i class="fa-solid fa-envelope icon-footer"></i>
    <p class="text-footer">© Copyright TinDog</p>

  </footer>


</body>

</html>
