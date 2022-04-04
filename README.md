<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8"/>
    <title>Bootstrap Website Two</title>
    <!-- GOOGLE FONT -->
    <link href="https://fonts.googleapis.com/css?family=Titillium+Web" rel="stylesheet" />
    <!-- BOOTSTRAP 4 -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
    <!-- SCROOLL REVEAL JS LIBRARY CDN -->
    <script src="https://unpkg.com/scrollreveal/dist/scrollreveal.min.js"></script>
    <!-- CUSTOM CSS -->
    <link rel="stylesheet" href="css/main.css">
  </head>
  <body>

    <!-- NAVIGATION -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
      <a class="navbar-brand" href="#">WebsiteTwo</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ml-auto">
          <a class="nav-item nav-link" href="#header">Informacion</a>
          <a class="nav-item nav-link" href="#info-one">Contacto con TI o facilities</a>
          <a class="nav-item nav-link" href="#contact">Formulario</a>
        </div>
      </div>
    </nav>

    <!-- SECTION -->
    <section id="header">
      <div class="container mt-5">
        <div class="row">
          <div class="col-md-6 col-sm-6">
            <div class="header-content-left">
              <img src="img/image1.png" style="width: 100%;">
            </div>  
          </div>
          <div class="col-md-6 col-sm-6">
            <div class="header-content-right">
              <h1 class="display-4">Informacion sobre este formulario</h1>
              <p class="mt-5">A continuacion observaran un formulario que nos ayudara con la comunicacion interdepartamental cuando la empresa tenga nuevos ingresos, este formulario debera ser llenado primeramente con el departamente de recursos humanos, siguiente con el gerente del nuevo empleado y por ultimo por el departamento de tecnologias de la informacion y facilities.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="testimonial">
      <div class="container">
        <p class="h2 mb-2">
          Hagamos sentir a nuestros nuevos companeros como en casa, dandoles todos la bienvenida a nuestro equipo de trabajo y apoyandolo en lo que necesite mientras se desarrolla con nosotros.
        </p>
      </div>
    </section>

    <section id="info-one">
      <div class="container">
        <div class="row mt-5">
          <div class="col-md-6">
            <div class="info-left">
              <img src="img/image2.png" style="width: 100%">
            </div>
          </div>
          <div class="col-md-6 my-auto">
            <div class="info-right">
              <h2>Contacto con el departamento de TI o Facilities</h2>
              <p>Para cualquier duda sobre este formulario, o contacto con alguien del personal de TI o Facilities, favor de dar un click en el boton para llamada via teams.</p>
              <a href="#" class="btn btn-outline-secondary btn-lg">Departamento de TI</a>
<a href="#" class="btn btn-outline-secondary btn-lg">Departamento de Facilities</a>

            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="info-two">
      <div class="container">
        <div class="row my-5">
          <div class="col-md-6">
          </div>
          <div class="col-md-6">
            <h2>Formulario!</h2>
          </div>
        </div>
      </div>
    </section>

    <footer id="contact">
      <div class="container">
        <div class="row">
          <div class="col-md-5">
            <form class="card mt-4">
              <div class="card-body">
                <div class="form-group">
                  <input type="text" class="form-control" placeholder="Nombre completo">
                </div>
                <div class="form-group">
                  <input type="text" class="form-control" 
placeholder="Departamento">
                </div>
                <div class="form-group">
                  <input type="text" class="form-control"
placeholder="Numero de empleado">
                </div>
                <div class="form-group">
                  <input type="text" class="form-control"  
placeholder="Coordenas de escritorio asignado">
                </div>
                <div class="form-group">
                  <input type="text" class="form-control"  
placeholder="Softwares a instalar">
                </div>
                <div class="form-group">
                  <input type="text" class="form-control"  

placeholder="Email">
                </div>
                <div class="form-group">
                  <textarea cols="30" rows="10" placeholder="Comentarios" class="form-control"></textarea>
                </div>
                <button class="btn btn-outline-secondary btn-block">
                  Send
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </footer>

    <!-- SCRIPTS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js" integrity="sha384-cs/chFZiN24E4KMATLdqdvsezGxaGsi4hLGOzlXwp5UZB1LY//20VyM2taTB4QvJ" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js" integrity="sha384-uefMccjFJAIv6A+rW+L4AHf99KvxDjWSu1z9VI8SKNVmz4sk7buKt/6v9KI65qnm" crossorigin="anonymous"></script>
    <!-- SCROOLL REVEAL SCRIPT -->
    <script>
      window.sr = ScrollReveal();

    sr.reveal('.navbar', {
      duration: 2000,
      origin: 'bottom'
    });

    sr.reveal('.header-content-left', {
      duration: 2000,
      origin: 'top',
      distance: '300px'
    });

    sr.reveal('.header-content-right', {
      duration: 2000,
      origin: 'right',
      distance: '300px'
    });

    sr.reveal('.header-btn', {
      duration: 2000,
      delay: 1000, 
      origin: 'bottom'
    });

    sr.reveal('#testimonial div', {
      duration: 2000,
      origin: 'left',
      distance: '300px',
      viewFactor: 0.2
    });

    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
    </script>
  </body>
</html>

