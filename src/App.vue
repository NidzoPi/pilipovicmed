<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
           <button type="button" class="btn btn-danger rounded-circle"> <a class="navbar-brand js-scroll-trigger" href="#page-top">Pilipović med</a></button>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto btn btn-danger">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#proizvodi">Proizvodi</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#about">O nama</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#team">Naš tim</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Kontakt</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Dobrodošli na našu web stranicu!</div>
          <div class="intro-heading text-uppercase stroke-text">Prirodno i naše</div>
          <a class="btn btn-primary btn-xl text-uppercase js-scroll-trigger" href="#about">Ko smo mi?</a>
        </div>
      </div>
    </header>

    <!-- Proizvodi Grid -->
    <Portfolio></Portfolio>

    <!-- About -->
    <section id="about">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">O nama</h2>
            <h3 class="section-subheading text-muted">Godinama radimo na kvalitetu.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <ul class="timeline">
              <li>
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="images/pcela.gif" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>1970</h4>
                    <h4 class="subheading">Naša priča počinje ovako</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Moj otac je bio 7. razred i kao svaki drugi dan kretao je u školu, ali ovaj dan
                    nije bio običan jer je na drvetu bilo nešto crno. Kada se primaknuo vidio je da je to roj pčela. Bio je
                    još dijete, ali veoma odvažan te je odlučio da udomi roj u trnku. Tako počinje naša priča.</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="images/pcela.gif" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>1980'</h4>
                    <h4 class="subheading">Još nije biznis</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Vremenom je otac zavolio pčele, ali nije razmišljao da napravi biznis već je samo proizvodio med za vlastite potrebe. Imao je stalan posao pa je pčele doživljavao kao hobi. </p>
                  </div>
                </div>
              </li>
              <li>
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="images/pcela.gif" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>1990'</h4>
                    <h4 class="subheading">Nesrećne 90'</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Čitav Balkan je bio pogođen sukobima koji su izmakli kontroli, tako da su mnogi ljudi kao i moji roditelji ostajali bez posla. Kasnije se nije baš moglo naći lako posla jer je sve bilo uništeno, ali pčele su preživjele. Roditelji se počinju baviti pčelarstvom i ljekovitim biljem ozbiljno.</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-image">
                  <img class="rounded-circle img-fluid" src="images/pcela.gif" alt="">
                </div>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2000 -> </h4>
                    <h4 class="subheading">21. vijek</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Pčelarstvo prerasta u biznis i osnovni izvor prihoda moje porodice. Sada brojimo oko 130 pčelinjih zajednica, ali ukoliko se ja odlučim baviti pčelarstvom planiramo proširenje.</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <div class="timeline-image">
                  <h4>Podrži nas
                    <br>i budi dio
                    <br>naše istorije!</h4>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Team -->
    <section class="bg-light" id="team">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Naš vrijedni tim</h2>
            <h3 class="section-subheading text-muted">Kvalitet,rad i istrajnost je ono što nas odlikuje.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="images/pcelica.png" alt="">
              <h4>Nikola Pilipović</h4>
              <p class="text-muted">Marketing i pomoćnik u pčelinjaku</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="images/pcelica.png" alt="">
              <h4>Ostoja Pilipović</h4>
              <p class="text-muted">Vlasnik svih pčela</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="images/pcelica.png" alt="">
              <h4>Veliborka Pilipović</h4>
              <p class="text-muted">Mozak porodice i pomoćnik u pčelinjaku</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-8 mx-auto text-center">
            <p class="large text-muted">Mi smo oni koji se trude da uzmu sve što priroda daje, a zauzvrat joj dajemo sve što očekuje.</p>
            <p class="large text-muted">Radom uspjevamo u tom i nudimo vama naše proizvode.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Clients -->


    <!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase btn btn-danger">Kontaktirajte nas</h2>
          </div>
        </div>
        <br>
        <div class="row">
          <div class="col-lg-12">
              <div class="row">
                <div class="col-md-4 img-hover-zoom">
                  <a href="viber://add?number=066167826"><img width="100px" src = "images/viber.png"/></a>
                </div>
                <div class="col-md-4 img-hover-zoom" style="padding-top:8px;" id="phoneimage">
                  <a href="tel:+38766167826"> <img width="80px" src = "images/phone.png"/> </a>
                </div>
                 <div class="col-md-4 img-hover-zoom" style="padding-top:5px;">
                  <a target="_blank" href="https://www.facebook.com/pilipovicmed/"><img width="100px" src = "images/facebook.png"/></a>
                </div>
                <div class="clearfix"></div>
              </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Copyright &copy; Nikola Pilipović 2019</span>
          </div>
          <div class="col-md-4">
            <ul class="list-inline social-buttons">
              
                <a href="https://www.olx.ba/profil/NikolaPi" target="_blank">
                    <img src="images/social/olxlogo.png">
                </a>
              
              
                <a href="https://www.facebook.com/pilipovicmed/" id="paddingtreba" target="_blank">
                  <img src="images/social/fblogo.png">
                </a>
              
              
                <a href="#" target="_blank">
                  <img src="images/social/instlogo.png">
                </a>
            
            </ul>
          </div>
          <div class="col-md-4">
            <ul class="list-inline quicklinks">
              <li class="list-inline-item">
                <a href="#">Privacy Policy</a>
              </li>
              <li class="list-inline-item">
                <a href="#">Terms of Use</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>

    <!-- Portfolio Modals -->

    <!-- Modal 1 -->
    <div class="portfolio-modal modal fade" id="portfolioModal1" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
          <div class="container">
            <div class="row">
              <div class="col-lg-8 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Kestenov med</h2>
                  <p class="item-intro text-muted">Popunite sva polja i naš operater će Vas nazvati uskoro.</p>
                  <img class="img-fluid d-block mx-auto" src="img/portfolio/01-full.jpg" alt="">
                    <form id="myform" method="post">
                      <div class="form-group">
                        <label for="usr">Naručujete</label>
                        <input type="disa" class="form-control" value="Kestenov med" id="kestenmed" name="kestenmed">
                      </div>
                      <div class="form-group">
                        <label for="usr">Ime i prezime:</label>
                        <input type="text" class="form-control" id="from" name="from">
                      </div>
                      <div class="form-group">
                        <label for="pwd">Broj telefona:</label>
                        <input type="text" class="form-control" id="phone" name="phone">
                      </div>
                      <button type="submit" class="btn btn-warning btn-lg">Naruči</button>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>


    <!-- Modal 2 -->
    <div class="portfolio-modal modal fade" id="portfolioModal2" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
          <div class="container">
            <div class="row">
              <div class="col-lg-8 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Bagremov med</h2>
                  <p class="item-intro text-muted">Trenutno nemamo na stanju.</p>
                  <img class="img-fluid d-block mx-auto" src="img/portfolio/02-full.jpg" alt="">
                  <p>Za više info pozovite broj: 066 - 167 - 826</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Modal 3 -->
    <div class="portfolio-modal modal fade" id="portfolioModal3" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
          <div class="container">
            <div class="row">
              <div class="col-lg-8 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Propolis kapi</h2>
                  <p class="item-intro text-muted">Trenutno nemamo na stanju.</p>
                  <img class="img-fluid d-block mx-auto" src="img/portfolio/02-full.jpg" alt="">
                  <p>Za više info pozovite broj: 066 - 167 - 826</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script type="text/javascript">

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  components: {
    Portfolio
  }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
