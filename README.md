# Ost-project-
Project 
.carousel{
    height: 500px;
    width: 1000px;
    margin: auto;
    /* border: 2px solid red; */
    border-radius: 10px;
}

.container{
    justify-content: space-evenly;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 20px;
}
[03/08, 11:52 am] sneha: <!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap Website</title>
  <link rel="stylesheet" href="bootstrap.css">
css bootstrap link 
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body>  
   <!--navbar code -->
  

  <nav class="navbar navbar-expand-lg bg-body-danger">
    <div class="container bg-primary text-secondary">
      <a class="navbar-brand" href="#">
        <img src="https://i.pinimg.com/736x/ca/84/5d/ca845d4e45b759e6c3f8438313d3845f.jpg" alt="Bootstrap" width="100"
          height="50">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">Join</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <!-- code for carousel -->

  <div id="carouselExample" class="carousel slide">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://images.unsplash.com/photo-1511385348-a52b4a160dc2?q=80&w=1814&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
          class="d-block " width="1000" height="500" alt="...">
      </div>
      <div class="carousel-item">
        <img
          src="https://images.unsplash.com/photo-1695891888323-661dbe27dc79?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
          class="d-block " width="1000" height="500" alt="...">
      </div>
      <div class="carousel-item">
        <img
          src="https://media.istockphoto.com/id/1857295289/photo/modern-creative-workplace-with-nobody-in-and-dual-displays-setup.jpg?s=2048x2048&w=is&k=20&c=KWA1_SmeM7EE2vpZIlAplmp5tiUfO7dDSIm4RyY9f18="
          class="d-block" width="1000" height="500" alt="...">
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


  <!-- cards section -->

  <div class="container d-flex justify-evenly">
    <div class="card" style="width: 18rem;">
      <img
        src="https://images.unsplash.com/photo-1511385348-a52b4a160dc2?q=80&w=1814&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
        class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Add to Card</a>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img
        src="https://images.unsplash.com/photo-1695891888323-661dbe27dc79?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
        class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Add to Card</a>
      </div>
    </div>
    <div class="card" style="width: 18rem;">
      <img
        src="https://media.istockphoto.com/id/1857295289/photo/modern-creative-workplace-with-nobody-in-and-dual-displays-setup.jpg?s=2048x2048&w=is&k=20&c=KWA1_SmeM7EE2vpZIlAplmp5tiUfO7dDSIm4RyY9f18="
        class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Add to Card</a>
      </div>
    </div>
  </div>
  </div>
  </div>

  <!-- script bootstrap link -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"></script>
</body>

</html> -->
