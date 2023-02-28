<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>My Portfolio | Galih</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous" />
    <!-- bootstrap icon -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css" />
    <!-- my css -->
    <link rel="stylesheet" href="style.css" />
    <!-- akhir my css -->
  </head>

  <body id="home">
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">Galih Prastowo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#projects">Project</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- akhir navbar -->

    <!-- jumbotron -->
    <section class="jumbotron text-center">
      <img src="img/saya.jpg" alt="Galih" width="200" class="rounded-circle img-thumbnail" />
      <h1 class="display-4">Galih Prastowo</h1>
      <p class="lead">Student | Universitas Teknologi Yogyakarta</p>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#ffffff"
          fill-opacity="1"
          d="M0,160L48,144C96,128,192,96,288,101.3C384,107,480,149,576,186.7C672,224,768,256,864,266.7C960,277,1056,267,1152,224C1248,181,1344,107,1392,69.3L1440,32L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- akhir jumbroton -->

    <!-- About -->
    <section id="about">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>About me</h2>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4">
            <p>ipsum dolor sit, amet consectetur adipisicing elit. Eum voluptatibus cum nam, a explicabo deserunt et natus nesciunt ipsam accusantium.</p>
          </div>
          <div class="col-md-4">
            <a>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam consectetur debitis, ullam delectus veniam itaque. Totam excepturi nisi fugiat autem!</a>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#e2edff"
          fill-opacity="1"
          d="M0,128L60,122.7C120,117,240,107,360,133.3C480,160,600,224,720,245.3C840,267,960,245,1080,218.7C1200,192,1320,160,1380,144L1440,128L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- Akhir About -->

    <!-- project -->
    <section id="projects">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>My project</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/1.jpg" class="card-img-top" alt="Project-1" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/2.jpg" class="card-img-top" alt="Project-2" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/3.jpg" class="card-img-top" alt="Project-3" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/4.jpg" class="card-img-top" alt="Project-4" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/5.jpg" class="card-img-top" alt="Project-5" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#ffffff"
          fill-opacity="1"
          d="M0,224L60,197.3C120,171,240,117,360,112C480,107,600,149,720,154.7C840,160,960,128,1080,128C1200,128,1320,160,1380,176L1440,192L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- Akhir Project -->

    <!-- contact -->
    <section id="contact">
      <div class="container">
        <div class="row text-center md-3">
          <div class="col">
            <h2>Contact Me</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <form>
              <div class="mb-3">
                <label for="name" class="form-label">Nama Lengkap</label>
                <input type="text" class="form-control" id="name" aria-describedby="name" />
              </div>
              <div class="mb-3">
                <label for="email1" class="form-label">Email</label>
                <input type="email" class="form-control" id="email1" aria-describedby="email" />
              </div>
              <div class="mb-3">
                <label for="pesan" class="form-label">Pesan</label>
                <textarea class="form-control" id="pesan" rows="3"></textarea>
              </div>

              <button type="submit" class="btn btn-primary">Submit</button>
            </form>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#0d6efd"
          fill-opacity="1"
          d="M0,128L60,154.7C120,181,240,235,360,229.3C480,224,600,160,720,165.3C840,171,960,245,1080,272C1200,299,1320,277,1380,266.7L1440,256L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- Akhir Contact -->

    <!-- footer -->
    <footer class="bg-primary text-white text-center pb-3">
      <p>Created with <i class="bi bi-heart-fill text-danger"></i> by <a href="https://www.instagram.com/gapra31/" class="text-white fw-bold">Galih Prastowo</a></p>
    </footer>
    <!-- Akhir footer -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
  </body>
</html>
