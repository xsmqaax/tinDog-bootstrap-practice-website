TinDog Starting Files
# tinDog-bootstrap-practice-website

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <!-- CSS only -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;400;900&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;400;900&family=Ubuntu:wght@300;400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>

<body>

  <section id="title">


    <div class="container-fluid">

      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-lg">
          <a class="navbar-brand mylogo " href="#">tindog</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link  linksto" aria-current="page" href="#">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link linksto" href="#">Pricing</a>
              </li>
              <li class="nav-item">
                <a class="nav-link linksto" href="#">Download</a>
              </li>
            </ul>
          </div>
      </nav>


      <!-- Title -->
      <div class="row">
        <div class="col-lg-6">
          <h1 class="intro-text">Meet new and interesting dogs nearby.</h1>
          <button type="button"  class="btn btn-dark btn-lg download-button" >Download</button>
          <button type="button"  class="btn btn-outline-light btn-lg download-button" >Download</button>
        </div>
        <div class="col-lg-6">
          <img class="title-image" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div> 
    </div>

  </section>

  <!-- Features -->

  <section id="features">
    <div class="row">
      <div class="features-box col-lg-4">
        <h3>Easy to use.</h3>
        <p>So easy to use, even your dog could do it.</p>
      </div>

      <div class="features-box col-lg-4">
        <h3>Elite Clientele</h3>
        <p>We have all the dogs, the greatest dogs.</p>
      </div>

      <div class="features-box col-lg-4">
        <h3>Guaranteed to work.</h3>
        <p>Find the love of your dog's life or your money back.</p>
      </div>

    </div>
  </section>


  <!-- Testimonials -->

  <section id="testimonials">






    <div id="testimonial-sliding" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
        
          <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
      
        </div>
        <div class="carousel-item">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
     
        </div>

      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#testimonial-sliding" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="false"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#testimonial-sliding" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="false"></span>
      </button>
    </div>

  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>


    <div class="row">
      <div class="pricing-column col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2>Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-outline-dark " type="button">Sign Up</button>
        
          </div>
        </div>
      </div>

      <div class="pricing-column col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Labrador</h3>
   
          </div>
          <div class="card-body">
    
            <h2>$49 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
          </div>
        </div>
      </div>

      <div class="pricing-column col-lg-4">
        <div class="card">
          <div class="card-header">
            <h3>Mastiff</h3>

          </div>
          <div class="card-body">
            <h2>$99 / mo</h2>
            <p>Pirority Listing</p>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
        
          </div>
        </div>
      </div>
    </div>

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="cta-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button class="download-button btn btn-lg btn-dark" type="button">Download</button>
    <button class="download-button btn btn-lg btn-light" type="button">Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <p>© Copyright Saad Alsayed`</p>

  </footer>





  <!-- JavaScript Bundle with Popper -->
</body>

</html>
