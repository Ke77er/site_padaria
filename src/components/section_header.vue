<template>
  <!-- Header -->
  <header class="kf-header">

    <!-- topline -->
    <div class="kf-topline">
      <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4">

          <!-- hours -->
          <div class="kf-h-group">
            <i class="far fa-clock"></i>
            <em>Horário de atendimento :</em><br> 08:00 da manhã - 09:00 da noite
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 align-center">

          <!-- social -->
          <div class="kf-h-social">
            <a href="" target="blank"><i class="fab fa-facebook-f"></i></a>
            <a href="" target="blank"><i class="fab fa-twitter"></i></a>
            <a href="" target="blank"><i class="fab fa-instagram"></i></a>
            <a href="" target="blank"><i class="fab fa-youtube"></i></a>
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-4 align-right">

          <!-- location -->
          <div class="kf-h-group">
            <i class="fas fa-map-marker-alt"></i>
            <em>Localização :</em> R. XV de Novembro, 8862 - Vila Nova, Joinville - SC, 89237-680
          </div>

        </div>
      </div>
    </div>

    <!-- navbar -->
    <div class="kf-navbar">
      <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-3 col-lg-3">

          <!-- logo -->
          <div class="kf-logo">
            <a href=""><img src="./src/assets/images/logo.png" alt="" /></a>
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-6 col-lg-6 align-center">

          <!-- main menu -->
          <div class="kf-main-menu">
            <ul>
              <li><a href="#Inicio">Inicio</a></li>
              <li><a href="#About">Sobre</a></li>
              <li>
                <a href="#Services">Menu<i class="las la-angle-down"></i></a>
                <ul>
                  <li><a href="#Doces">Menu de Doces</a></li>
                  <li><a href="#Salgados">Menu do Salgados</a></li>
                  <li><a href="#Conveniencia">Conveniência</a></li>
                  <li><a href="#Restaurante">Restaurante</a></li>
                </ul>
              </li>
              <li><a href="#Contato">Contato</a></li>
            </ul>
          </div>

        </div>
        <div class="col-xs-12 col-sm-6 col-md-3 col-lg-3 align-right">

          <!-- menu btn -->
          <a href="#" class="kf-menu-btn"><span></span></a>

          <!-- btn -->
          <a onclick="window.open('https://7-graos-almoco.ola.click/products', '_blank');" class="kf-btn h-btn">
            <span>Peça o Delivery</span>
          </a>

        </div>
      </div>
    </div>

    <!-- mobile navbar -->
    <div class="kf-navbar-mobile">

      <!-- mobile menu -->
      <div class="kf-main-menu">
        <ul>
          <li class="has-children">
            <a href="#Inicio">Inicio</a>
          </li>
          <li><a href="#About">Sobre</a></li>
          <li class="has-children">
            <a href="#Services">Menu</a>
            <i class="las la-angle-down"></i>
            <ul>
              <li><a href="#Doces">Menu de Doces</a></li>
              <li><a href="#Salgados">Menu do Salgados</a></li>
              <li><a href="#Conveniencia">Conveniência</a></li>
              <li><a href="#Restaurante">Restaurante</a></li>
            </ul>
          </li>
          <li><a href="#Contato">Contato</a></li>
        </ul>
      </div>

      <!-- mobile topline -->
      <div class="kf-topline">
        <div class="row">
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

            <!-- mobile btn -->
            <a onclick="window.open('https://7-graos-almoco.ola.click/products', '_blank');" class="kf-btn h-btn">
              <span>Peça o Delivery</span>
              <i class="fas fa-chevron-right"></i>
            </a>

          </div>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

            <!-- social -->
            <div class="kf-h-social">
              <a href="" target="blank"><i class="fab fa-facebook-f"></i></a>
              <a href="" target="blank"><i class="fab fa-twitter"></i></a>
              <a href="" target="blank"><i class="fab fa-instagram"></i></a>
              <a href="" target="blank"><i class="fab fa-youtube"></i></a>
            </div>

          </div>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

            <!-- hours -->
            <div class="kf-h-group">
              <i class="far fa-clock"></i>
              <em>Horário de atendimento :</em><br> 08:00 da manhã - 09:00 da noite
            </div>

          </div>
          <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">

            <!-- location -->
            <div class="kf-h-group">
              <i class="fas fa-map-marker-alt"></i>
              <em>Localização :</em> R. XV de Novembro, 8862 - Vila Nova, Joinville - SC, 89237-680
            </div>

          </div>
        </div>
      </div>

    </div>

  </header>
</template>

<script>
export default {
  name: "SectionHeader",
  data() {
    return {
    };
  },
  methods: {
  }
}
</script>


<style scoped></style>