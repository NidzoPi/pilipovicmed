<template>
    <section class="bg-light" id="proizvodi">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Proizvodi</h2>
            <h3 class="section-subheading text-muted">Testiranje naših proizvoda dozvoljeno u bilo kojoj laboratoriji.</h3>
          </div>
        </div>
        <div class="row">
          
            <div class="col-md-4 col-sm-6 portfolio-item" v-for="(obj, key) in portfolioJSON" :key="key">
                <a class="portfolio-link" data-toggle="modal" :href="obj.modal">
                    <div class="portfolio-hover">
                        <div class="portfolio-hover-content">
                              <h3> NARUČI </h3>
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="img/portfolio/02-thumbnail.jpg" alt="">                   
                
                <div class="portfolio-caption">
                    <h4>{{ obj.caption }}</h4> <br>
                    <p class="text-muted">{{ obj.title }}</p> <br>
                    <img width="250px"  height="250px" :src="obj.img"/>
                    <p class="text-muted">Cijena: {{obj.price}}</p>
                </div>
                </a>
            </div>
        </div>
      </div>
      <h3 class="section-subheading text-muted">Klikni na proizvod i naruči.</h3>
    </section>
</template>

<script>
export default {
    data: () => ({
        portfolioJSON: [
            {
                img: 'images/kestenmed.jpg',
                caption: 'Kestenov med',
                title: 'Najkvalitetniji med na svijetu',
                price: '15 KM',
                modal: '#portfolioModal1'
            },
            {
                img: 'images/bagremmed.jpg',
                caption: 'Bagremov med',
                title: 'Okus koji osvaja',
                price: '15 KM',
                modal: '#portfolioModal2'
            },
            {
                img: 'images/propolis.jpeg',
                caption: 'Propolis kapi',
                title: 'Jača imunitet, ubija bakterije',
                price: '3 KM',
                modal: '#portfolioModal3'
            }
   
        ]
    })
}
</script>

<style lang="css">

</style>


