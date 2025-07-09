<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meus calçados oficial</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./assets/images/logo/favicon.ico" type="image/x-icon">

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style-prefix.css">

  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap"
    rel="stylesheet">

</head>

<body>


  <div class="overlay" data-overlay></div>

  <!--
    - MODAL
  -->

  <div class="modal" data-modal>

    <div class="modal-close-overlay" data-modal-overlay></div>

    <div class="modal-content">

      <button class="modal-close-btn" data-modal-close>
        <ion-icon name="close-outline"></ion-icon>
      </button>

      <div class="newsletter-img">
        <img src="./assets/images/newsletter.png" alt="subscribe newsletter" width="400" height="400">
      </div>

      <div class="newsletter">

        <form action="#">

          <div class="newsletter-header">

            <h3 class="newsletter-title">Se junte a nós.</h3>

            <p class="newsletter-desc">
              Se inscreva em <b>Meus calçados</b> para conseguir os produto mais recentes e discontos atualizados.
            </p>

          </div>

          <input type="email" name="email" class="email-field" placeholder="Endereço de e-mail" required>

          <button type="submit" class="btn-newsletter">Inscreva-se</button>

        </form>

      </div>

    </div>

  </div>





  <!--
    - NOTIFICATION TOAST
  -->

  <div class="notification-toast" data-toast>

    <button class="toast-close-btn" data-toast-close>
      <ion-icon name="close-outline"></ion-icon>
    </button>

    <div class="toast-banner">
      <img src="./assets/images/products/Chuck Taylor All Star Vermelho.jpg" alt="Rose Gold Earrings" width="80" height="70">
    </div>

    <div class="toast-detail">

      <p class="toast-message">
        Alguém novo comprou o produto
      </p>

      <p class="toast-title">
        Chuck Taylor All Star Vermelho
      </p>

      <p class="toast-meta">
        <time datetime="PT2M">2 Minutos</time> atrás
      </p>

    </div>

  </div>





  <!--
    - HEADER
  -->

  <header>

    <div class="header-top">

      <div class="container">

        <ul class="header-social-container">

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li>

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a>
          </li>

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </li>

        </ul>

        <div class="header-alert-news">
          <p>
            <b>Envio grátis</b>
            esta semana acima de - $55
          </p>
        </div>

        <div class="header-top-actions">

          <select name="currency">

            <option value="usd">R &dollar;</option>
            <option value="eur">US &euro;</option>

          </select>

          <select name="language">

            <option value="pt-BR">português</option>
            <option value="en-US">ingl&ecirc;s</option>
            <option value="es-ES">espa&ntilde;hol</option>

          </select>

        </div>

      </div>

    </div>

    <div class="header-main">

      <div class="container">

        <a href="#" class="header-logo">
          <img src="./assets/images/logo/logo.svg" alt="Anon's logo" width="120" height="36">
        </a>

        <div class="header-search-container">

          <input type="search" name="search" class="search-field" placeholder="Digite o nome do seu produto...">

          <button class="search-btn">
            <ion-icon name="search-outline"></ion-icon>
          </button>

        </div>

        <div class="header-user-actions">

          <button class="action-btn">
            <ion-icon name="person-outline"></ion-icon>
          </button>

          <button class="action-btn">
            <ion-icon name="heart-outline"></ion-icon>
            <span class="count">0</span>
          </button>

          <button class="action-btn">
            <ion-icon name="bag-handle-outline"></ion-icon>
            <span class="count">0</span>
          </button>

        </div>

      </div>

    </div>

    <nav class="desktop-navigation-menu">

      <div class="container">

        <ul class="desktop-menu-category-list">

          <li class="menu-category">
            <a href="#" class="menu-title">Início</a>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Categorias</a>

            <div class="dropdown-panel">

              <ul class="dropdown-panel-list">

                <li class="menu-title">
                  <a href="#">Marcas</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Nike</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Adidas</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">All star</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Star feet</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Havaianas</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">
                    <img src="./assets/images/electronics-banner-1.jpg" alt="headphone collection" width="250"
                      height="119">
                  </a>
                </li>

              </ul>

              <ul class="dropdown-panel-list">

                <li class="menu-title">
                  <a href="#">Masculino</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Formal</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Infantil</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Esporte</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Escolar</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Praia</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">
                    <img src="./assets/images/mens-banner.jpg" alt="men's fashion" width="250" height="119">
                  </a>
                </li>

              </ul>

              <ul class="dropdown-panel-list">

                <li class="menu-title">
                  <a href="#">Feminino</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Formal</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Infantil</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Esporte</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Escolar</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Praia</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">
                    <img src="./assets/images/womens-banner.jpg" alt="women's fashion" width="250" height="119">
                  </a>
                </li>

              </ul>

              <ul class="dropdown-panel-list">

                <li class="menu-title">
                  <a href="#">Acessórios</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Cadarço</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Meia</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Palmilha</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Calçadeiras</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">Calcanheira</a>
                </li>

                <li class="panel-list-item">
                  <a href="#">
                    <img src="./assets/images/electronics-banner-2.jpg" alt="mouse collection" width="250" height="119">
                  </a>
                </li>

              </ul>

            </div>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Masculino</a>

            <ul class="dropdown-list">

              <li class="dropdown-item">
                <a href="#">tênis</a>
              </li>

              <li class="dropdown-item">
                <a href="#">sapato social</a>
              </li>

              <li class="dropdown-item">
                <a href="#">chuteira</a>
              </li>

              <li class="dropdown-item">
                <a href="#">mocassin</a>
              </li>

            </ul>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Feminino</a>

            <ul class="dropdown-list">

              <li class="dropdown-item">
                <a href="#">tênis</a>
              </li>

              <li class="dropdown-item">
                <a href="#">salto alto</a>
              </li>

              <li class="dropdown-item">
                <a href="#">sapatilha</a>
              </li>

              <li class="dropdown-item">
                <a href="#">sandália</a>
              </li>

            </ul>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Casual</a>

            <ul class="dropdown-list">

              <li class="dropdown-item">
                <a href="#">chinelo</a>
              </li>

              <li class="dropdown-item">
                <a href="#">tênis</a>
              </li>

              <li class="dropdown-item">
                <a href="#">sandália</a>
              </li>

              <li class="dropdown-item">
                <a href="#">rasteirinha</a>
              </li>

            </ul>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Formal</a>

            <ul class="dropdown-list">

              <li class="dropdown-item">
                <a href="#">mocassin</a>
              </li>

              <li class="dropdown-item">
                <a href="#">oxford</a>
              </li>

              <li class="dropdown-item">
                <a href="#">salto alto</a>
              </li>

              <li class="dropdown-item">
                <a href="#">scarpin</a>
              </li>

            </ul>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Sobre nós</a>
          </li>

          <li class="menu-category">
            <a href="#" class="menu-title">Ofertas quentes</a>
          </li>

        </ul>

      </div>

    </nav>

    <div class="mobile-bottom-navigation">

      <button class="action-btn" data-mobile-menu-open-btn>
        <ion-icon name="menu-outline"></ion-icon>
      </button>

      <button class="action-btn">
        <ion-icon name="bag-handle-outline"></ion-icon>

        <span class="count">0</span>
      </button>

      <button class="action-btn">
        <ion-icon name="home-outline"></ion-icon>
      </button>

      <button class="action-btn">
        <ion-icon name="heart-outline"></ion-icon>

        <span class="count">0</span>
      </button>

      <button class="action-btn" data-mobile-menu-open-btn>
        <ion-icon name="grid-outline"></ion-icon>
      </button>

    </div>

    <nav class="mobile-navigation-menu  has-scrollbar" data-mobile-menu>

      <div class="menu-top">
        <h2 class="menu-title">Menu</h2>

        <button class="menu-close-btn" data-mobile-menu-close-btn>
          <ion-icon name="close-outline"></ion-icon>
        </button>
      </div>

      <ul class="mobile-menu-category-list">

        <li class="menu-category">
          <a href="#" class="menu-title">Home</a>
        </li>

        <li class="menu-category">

          <button class="accordion-menu" data-accordion-btn>
            <p class="menu-title">Men's</p>

            <div>
              <ion-icon name="add-outline" class="add-icon"></ion-icon>
              <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
            </div>
          </button>

          <ul class="submenu-category-list" data-accordion>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Shirt</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Shorts & Jeans</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Safety Shoes</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Wallet</a>
            </li>

          </ul>

        </li>

        <li class="menu-category">

          <button class="accordion-menu" data-accordion-btn>
            <p class="menu-title">Women's</p>

            <div>
              <ion-icon name="add-outline" class="add-icon"></ion-icon>
              <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
            </div>
          </button>

          <ul class="submenu-category-list" data-accordion>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Dress & Frock</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Earrings</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Necklace</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Makeup Kit</a>
            </li>

          </ul>

        </li>

        <li class="menu-category">

          <button class="accordion-menu" data-accordion-btn>
            <p class="menu-title">Jewelry</p>

            <div>
              <ion-icon name="add-outline" class="add-icon"></ion-icon>
              <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
            </div>
          </button>

          <ul class="submenu-category-list" data-accordion>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Earrings</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Couple Rings</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Necklace</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Bracelets</a>
            </li>

          </ul>

        </li>

        <li class="menu-category">

          <button class="accordion-menu" data-accordion-btn>
            <p class="menu-title">Perfume</p>

            <div>
              <ion-icon name="add-outline" class="add-icon"></ion-icon>
              <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
            </div>
          </button>

          <ul class="submenu-category-list" data-accordion>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Clothes Perfume</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Deodorant</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Flower Fragrance</a>
            </li>

            <li class="submenu-category">
              <a href="#" class="submenu-title">Air Freshener</a>
            </li>

          </ul>

        </li>

        <li class="menu-category">
          <a href="#" class="menu-title">Blog</a>
        </li>

        <li class="menu-category">
          <a href="#" class="menu-title">Hot Offers</a>
        </li>

      </ul>

      <div class="menu-bottom">

        <ul class="menu-category-list">

          <li class="menu-category">

            <button class="accordion-menu" data-accordion-btn>
              <p class="menu-title">Language</p>

              <ion-icon name="caret-back-outline" class="caret-back"></ion-icon>
            </button>

            <ul class="submenu-category-list" data-accordion>

              <li class="submenu-category">
                <a href="#" class="submenu-title">English</a>
              </li>

              <li class="submenu-category">
                <a href="#" class="submenu-title">Espa&ntilde;ol</a>
              </li>

              <li class="submenu-category">
                <a href="#" class="submenu-title">Fren&ccedil;h</a>
              </li>

            </ul>

          </li>

          <li class="menu-category">
            <button class="accordion-menu" data-accordion-btn>
              <p class="menu-title">Currency</p>
              <ion-icon name="caret-back-outline" class="caret-back"></ion-icon>
            </button>

            <ul class="submenu-category-list" data-accordion>
              <li class="submenu-category">
                <a href="#" class="submenu-title">USD &dollar;</a>
              </li>

              <li class="submenu-category">
                <a href="#" class="submenu-title">EUR &euro;</a>
              </li>
            </ul>
          </li>

        </ul>

        <ul class="menu-social-container">

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li>

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a>
          </li>

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li>
            <a href="#" class="social-link">
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </li>

        </ul>

      </div>

    </nav>

  </header>





  <!--
    - MAIN
  -->

  <main>

    <!--
      - BANNER
    -->

    <div class="banner">

      <div class="container">

        <div class="slider-container has-scrollbar">

          <div class="slider-item">

            <img src="./assets/images/banner-1.jpg" alt="women's latest fashion sale" class="banner-img">

            <div class="banner-content">

              <p class="banner-subtitle">tendências</p>

              <h2 class="banner-title">A moda mais recente a venda</h2>

              <p class="banner-text">
                a partir de &dollar; <b>39</b>.99
              </p>

              <a href="#" class="banner-btn">compre agora</a>

            </div>

          </div>

          <div class="slider-item">

            <img src="./assets/images/banner-2.jpg" alt="modern sunglasses" class="banner-img">

            <div class="banner-content">

              <p class="banner-subtitle">Estilo</p>

              <h2 class="banner-title">Tênis casual</h2>

              <p class="banner-text">
                a partir de &dollar; <b>20</b>.00
              </p>

              <a href="#" class="banner-btn">compre agora</a>

            </div>

          </div>

          <div class="slider-item">

            <img src="./assets/images/banner-3.jpg" alt="new fashion summer sale" class="banner-img">

            <div class="banner-content">

              <p class="banner-subtitle">oferta a venda</p>

              <h2 class="banner-title">Novo estilo para o inverno</h2>

              <p class="banner-text">
                a partir de &dollar; <b>19</b>.99
              </p>

              <a href="#" class="banner-btn">compre agora</a>

            </div>

          </div>

        </div>

      </div>

    </div>





    <!--
      - CATEGORY
    -->

    <div class="category">

      <div class="container">

        <div class="category-item-container has-scrollbar">

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/sandália.svg" alt="dress & frock" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">sandálias</h3>

                <p class="category-item-amount">(53)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/sapatilha.svg" alt="winter wear" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">sapatilhas</h3>

                <p class="category-item-amount">(58)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/palmilha.svg" alt="glasses & lens" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">palmilhas</h3>

                <p class="category-item-amount">(68)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/cadarço.svg" alt="shorts & jeans" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">cadarços</h3>

                <p class="category-item-amount">(84)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/EPIs.svg" alt="t-shirts" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">EPI-s</h3>

                <p class="category-item-amount">(35)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/oxford.svg" alt="jacket" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">oxfords</h3>

                <p class="category-item-amount">(16)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/bota.svg" alt="watch" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">botas</h3>

                <p class="category-item-amount">(27)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

          <div class="category-item">

            <div class="category-img-box">
              <img src="./assets/images/icons/meia.svg" alt="hat & caps" width="30">
            </div>

            <div class="category-content-box">

              <div class="category-content-flex">
                <h3 class="category-item-title">meias</h3>

                <p class="category-item-amount">(39)</p>
              </div>

              <a href="#" class="category-btn">mostrar tudo</a>

            </div>

          </div>

        </div>

      </div>

    </div>





    <!--
      - PRODUCT
    -->

    <div class="product-container">

      <div class="container">


        <!--
          - SIDEBAR
        -->

        <div class="sidebar  has-scrollbar" data-mobile-menu>

          <div class="sidebar-category">

            <div class="sidebar-top">
              <h2 class="sidebar-title">Categoria</h2>

              <button class="sidebar-close-btn" data-mobile-menu-close-btn>
                <ion-icon name="close-outline"></ion-icon>
              </button>
            </div>

            <ul class="sidebar-menu-category-list">

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/tênis.svg" alt="clothes" width="20" height="20"
                      class="menu-title-img">

                    <p class="menu-title">tênis</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">All star</p>
                      <data value="30" class="stock" title="Available Stock">30</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Nike</p>
                      <data value="60" class="stock" title="Available Stock">60</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Vans</p>
                      <data value="50" class="stock" title="Available Stock">50</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Olympikus</p>
                      <data value="5" class="stock" title="Available Stock">5</data>
                    </a>
                  </li>

                </ul>

              </li>

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/chuteira.svg" alt="footwear" class="menu-title-img" width="20"
                      height="20">

                    <p class="menu-title">chuteiras</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Adidas</p>
                      <data value="45" class="stock" title="Available Stock">45</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Nike</p>
                      <data value="5" class="stock" title="Available Stock">5</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Cronos</p>
                      <data value="35" class="stock" title="Available Stock">35</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Umbro</p>
                      <data value="26" class="stock" title="Available Stock">26</data>
                    </a>
                  </li>

                </ul>

              </li>

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/chinelo.svg" alt="clothes" class="menu-title-img" width="20"
                      height="20">

                    <p class="menu-title">chinelos</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Havaianas</p>
                      <data value="46" class="stock" title="Available Stock">46</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Nike</p>
                      <data value="73" class="stock" title="Available Stock">73</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Rider</p>
                      <data value="61" class="stock" title="Available Stock">61</data>
                    </a>
                  </li>
                  
                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Olympikus</p>
                      <data value="42" class="stock" title="Available Stock">42</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Ipanema</p>
                      <data value="30" class="stock" title="Available Stock">30</data>
                    </a>
                  </li>    

                </ul>

              </li>

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/mocassin.svg" alt="perfume" class="menu-title-img" width="20"
                      height="20">

                    <p class="menu-title">mocassins</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Andacco</p>
                      <data value="62" class="stock" title="Available Stock">62</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Art nobre</p>
                      <data value="50" class="stock" title="Available Stock">50</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Hugo boss</p>
                      <data value="81" class="stock" title="Available Stock">81</data>
                    </a>
                  </li>

                </ul>

              </li>

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/sapato social.svg" alt="cosmetics" class="menu-title-img" width="20"
                      height="20">

                    <p class="menu-title">sapato social</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Schiareli</p>
                      <data value="55" class="stock" title="Available Stock">55</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Sândalo</p>
                      <data value="77" class="stock" title="Available Stock">77</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Woche</p>
                      <data value="12" class="stock" title="Available Stock">12</data>
                    </a>
                  </li>

                </ul>

              </li>

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/rasteirinha.svg" alt="glasses" class="menu-title-img" width="20"
                      height="20">

                    <p class="menu-title">rasteirinhas</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Via miss</p>
                      <data value="69" class="stock" title="Available Stock">69</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Menina fashion</p>
                      <data value="47" class="stock" title="Available Stock">47</data>
                    </a>
                  </li>

                </ul>

              </li>

              <li class="sidebar-menu-category">

                <button class="sidebar-accordion-menu" data-accordion-btn>

                  <div class="menu-title-flex">
                    <img src="./assets/images/icons/salto alto.svg" alt="bags" class="menu-title-img" width="20" height="20">

                    <p class="menu-title">salto alto</p>
                  </div>

                  <div>
                    <ion-icon name="add-outline" class="add-icon"></ion-icon>
                    <ion-icon name="remove-outline" class="remove-icon"></ion-icon>
                  </div>

                </button>

                <ul class="sidebar-submenu-category-list" data-accordion>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Cecconello</p>
                      <data value="62" class="stock" title="Available Stock">62</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Vizzano</p>
                      <data value="38" class="stock" title="Available Stock">38</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Gats</p>
                      <data value="10" class="stock" title="Available Stock">10</data>
                    </a>
                  </li>

                  <li class="sidebar-submenu-category">
                    <a href="#" class="sidebar-submenu-title">
                      <p class="product-name">Beira rio</p>
                      <data value="4" class="stock" title="Available Stock">4</data>
                    </a>
                  </li>

                </ul>

              </li>

            </ul>

          </div>

          <div class="product-showcase">

            <h3 class="showcase-heading">melhores vendedores</h3>

            <div class="showcase-wrapper">

              <div class="showcase-container">

                <div class="showcase">

                  <a href="#" class="showcase-img-box">
                    <img src="./assets/images/products/Meia Lupo Sport Walk Cano Curto 3 Pares.jpg" alt="baby fabric shoes" width="75" height="75"
                      class="showcase-img">
                  </a>

                  <div class="showcase-content">

                    <a href="#">
                      <h4 class="showcase-title">Meia Lupo Sport Walk Cano Curto 3 Pares</h4>
                    </a>

                    <div class="showcase-rating">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                    </div>

                    <div class="price-box">
                      <del>$4.49</del>
                      <p class="price">$4.00</p>
                    </div>

                  </div>

                </div>

                <div class="showcase">

                  <a href="#" class="showcase-img-box">
                    <img src="./assets/images/products/Palmilha Confort Pé Relax  Pé Relax Sapatos Confortáveis.jpg" alt="men's hoodies t-shirt" class="showcase-img"
                      width="75" height="75">
                  </a>

                  <div class="showcase-content">

                    <a href="#">
                      <h4 class="showcase-title">Palmilha Confort Pé Relax</h4>
                    </a>
                    <div class="showcase-rating">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star-half-outline"></ion-icon>
                    </div>

                    <div class="price-box">
                      <del>$12.00</del>
                      <p class="price">$7.00</p>
                    </div>

                  </div>

                </div>

                <div class="showcase">

                  <a href="#" class="showcase-img-box">
                    <img src="./assets/images/products/CADARÇO CHATO ALG SCERA 32285 - 90CM - ROXO - romeucouros.jpg" alt="girls t-shirt" class="showcase-img" width="75"
                      height="75">
                  </a>

                  <div class="showcase-content">

                    <a href="#">
                      <h4 class="showcase-title">Cadarço chato alg scera 32285 - 90cm - roxo - romeucouros</h4>
                    </a>
                    <div class="showcase-rating">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star-half-outline"></ion-icon>
                    </div>

                    <div class="price-box">
                      <del>$4.00</del>
                      <p class="price">$2.00</p>
                    </div>

                  </div>

                </div>

                <div class="showcase">

                  <a href="#" class="showcase-img-box">
                    <img src="./assets/images/products/Cadarço Chato Poliester T150 - 120cm - Cinza Escuro - Par.jpg" alt="woolen hat for men" class="showcase-img" width="75"
                      height="75">
                  </a>

                  <div class="showcase-content">

                    <a href="#">
                      <h4 class="showcase-title">Cadarço Chato Poliester T150 - 120cm - Cinza Escuro - Par</h4>
                    </a>
                    <div class="showcase-rating">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                    </div>

                    <div class="price-box">
                      <del>$6.00</del>
                      <p class="price">$3.00</p>
                    </div>

                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>



        <div class="product-box">

          <!--
            - PRODUCT MINIMAL
          -->

          <div class="product-minimal">

            <div class="product-showcase">

              <h2 class="title">Recém chegadas</h2>

              <div class="showcase-wrapper has-scrollbar">

                <div class="showcase-container">

                  <div class="showcase">

                    <a href="https://www.iriacalcados.com.br/sandalia-havaianas-brasil-logo-fc-azul-naval?srsltid=AfmBOooM-XBMH-DC-O772Mk2OBp1rHhPalJMGlopX1fX_6g3wKneuLn8" class="showcase-img-box">
                      <img src="./assets/images/products/Chinelo Havaianas Brasil Logo - Azul.jpg" alt="relaxed short full sleeve t-shirt" width="70" class="showcase-img">
                    </a>

                    <div class="showcase-content">

                      <a href="https://www.iriacalcados.com.br/sandalia-havaianas-brasil-logo-fc-azul-naval?srsltid=AfmBOooM-XBMH-DC-O772Mk2OBp1rHhPalJMGlopX1fX_6g3wKneuLn8">
                        <h4 class="showcase-title">Chinelo Havaianas Brasil Logo - Azul</h4>
                      </a>

                      <a href="#" class="showcase-category">chinelos</a>

                      <div class="price-box">
                        <p class="price">$77.90</p>
                        <del>$87.90</del>
                      </div>

                    </div>

                  </div>

                  <div class="showcase">
                  
                    <a href="https://www.bayardesportes.com.br/chinelo-slide-nike-victori-one-masculino-marinho/p?srsltid=AfmBOoqinn2n3mIZWZba4Xi5lowH72jLPqYY554BEhZM-P_pzeRYivKX" class="showcase-img-box">
                      <img src="./assets/images/products/NIKE VICTORI ONE MEN'S SLIDES.jpg" alt="girls pink embro design top" class="showcase-img" width="70">
                    </a>
                  
                    <div class="showcase-content">
                  
                      <a href="https://www.bayardesportes.com.br/chinelo-slide-nike-victori-one-masculino-marinho/p?srsltid=AfmBOoqinn2n3mIZWZba4Xi5lowH72jLPqYY554BEhZM-P_pzeRYivKX">
                        <h4 class="showcase-title">NIKE VICTORI ONE MEN'S SLIDES</h4>
                      </a>

                      <a href="#" class="showcase-category">chinelos</a>

                      <div class="price-box">
                        <p class="price">$189.90</p>
                        <del>$249.99</del>
                      </div>
                  
                    </div>
                  
                  </div>

                  <div class="showcase">
                
                    <a href="https://www.magazineluiza.com.br/sapatilha-feminina-moleca-5027-1407-preto/p/gf69fbg25j/md/spth/" class="showcase-img-box">
                      <img src="./assets/images/products/Sapatilha Moleca 5027.1407 - Preto - 36.jpg" alt="black floral wrap midi skirt" class="showcase-img"
                        width="70">

                    </a>
                  
                    <div class="showcase-content">
                  
                      <a href="https://www.magazineluiza.com.br/sapatilha-feminina-moleca-5027-1407-preto/p/gf69fbg25j/md/spth/">
                        <h4 class="showcase-title">Sapatilha Moleca 5027.1407 - Preto - 36</h4>
                      </a>
                  
                      <a href="#" class="showcase-category">sapatilhas</a>
                  
                      <div class="price-box">
                        <p class="price">$80.49</p>
                        <del>$90.49</del>
                      </div>
                  
                    </div>
                  
                  </div>

                  <div class="showcase">
                  
                    <a href="https://www.lojasrenner.com.br/p/chinelo-masc-dedo-rider-feel-urban-12318-au459/-/A-7010704602420-br.lr?srsltid=AfmBOooyo0JB5IxT8bO00u8LUzDGsF_F2p3A-CL44XBxwDuaxPQq_Zar&sku=7510709492437" class="showcase-img-box">
                      <img src="./assets/images/products/Chinelo Masc Dedo Rider Feel Urban 12318-Au459 Azul.jpg" alt="pure garment dyed cotton shirt" class="showcase-img"
                        width="70">
                    </a>
                  
                    <div class="showcase-content">
                  
                      <a href="https://www.lojasrenner.com.br/p/chinelo-masc-dedo-rider-feel-urban-12318-au459/-/A-7010704602420-br.lr?srsltid=AfmBOooyo0JB5IxT8bO00u8LUzDGsF_F2p3A-CL44XBxwDuaxPQq_Zar&sku=7510709492437">
                        <h4 class="showcase-title">Chinelo Masc Dedo Rider Feel Urban 12318-Au459 Azul</h4>
                      </a>
                  
                      <a href="#" class="showcase-category">chinelos</a>
                  
                      <div class="price-box">
                        <p class="price">$41.88</p>
                        <del>$51.88</del>
                      </div>
                  
                    </div>
                  
                  </div>

                </div>

                <div class="showcase-container">
                
                  <div class="showcase">
                
                    <a href="https://www.spazziojeans.com.br/tenis-nike-renew-run-3-feminino-rosa-e-vermelho?&sort=p.date_added&order=DESC&page=62" class="showcase-img-box">
                      <img src="./assets/images/products/Tênis Nike Renew Run 3 Feminino - Vermelho.jpg" alt="men yarn fleece full-zip jacket" class="showcase-img"
                        width="70">
                    </a>
                
                    <div class="showcase-content">
                
                      <a href="https://www.spazziojeans.com.br/tenis-nike-renew-run-3-feminino-rosa-e-vermelho?&sort=p.date_added&order=DESC&page=62">
                        <h4 class="showcase-title">Tênis Nike Renew Run 3 Feminino - Vermelho</h4>
                      </a>
                
                      <a href="#" class="showcase-category">tênis</a>
                
                      <div class="price-box">
                        <p class="price">$449.94</p>
                        <del>$749.90</del>
                      </div>
                
                    </div>
                
                  </div>
                
                  <div class="showcase">
                
                    <a href="https://viamiss.com.br/sandalia-rasteira-strass-dedo-no-marfim-rr1014-163?srsltid=AfmBOoqoNtrH-WFIwdE--YvIGeV7Vo1qWZIGZUO628LoOAS-4E8t2Qpp" class="showcase-img-box">
                      <img src="./assets/images/products/Sandália Rasteira Sunflower Marfim.jpg" alt="mens winter leathers jackets" class="showcase-img"
                        width="70">
                    </a>
                
                    <div class="showcase-content">
                
                      <a href="https://viamiss.com.br/sandalia-rasteira-strass-dedo-no-marfim-rr1014-163?srsltid=AfmBOoqoNtrH-WFIwdE--YvIGeV7Vo1qWZIGZUO628LoOAS-4E8t2Qpp">
                        <h4 class="showcase-title">Sandália Rasteira Sunflower Marfim Via miss</h4>
                      </a>
                
                      <a href="#" class="showcase-category">sandálias</a>
                
                      <div class="price-box">
                        <p class="price">$129.90</p>
                        <del>$139.90</del>
                      </div>
                
                    </div>
                
                  </div>
                
                  <div class="showcase">
                
                    <a href="https://www.layneshoes.com.br/categoria-feminino-saltos/sandalia-vizzano-salto-geometrico-tira-com-fivela-preto?srsltid=AfmBOorkMwMN-5zw_MauraGsgktj8ahnmWzcCvJNzNU3Q9IqWprz8Sep&variant_id=87160" class="showcase-img-box">
                      <img src="./assets/images/products/Sandália Feminina Vizzano Salto Geométrico Preto - 38.jpg" alt="mens winter leathers jackets" class="showcase-img"
                        width="70">
                    </a>
                
                    <div class="showcase-content">
                
                      <a href="https://www.layneshoes.com.br/categoria-feminino-saltos/sandalia-vizzano-salto-geometrico-tira-com-fivela-preto?srsltid=AfmBOorkMwMN-5zw_MauraGsgktj8ahnmWzcCvJNzNU3Q9IqWprz8Sep&variant_id=87160">
                        <h4 class="showcase-title">Sandália Feminina Vizzano Salto Geométrico Preto - 38</h4>
                      </a>
                
                      <a href="#" class="showcase-category">sandálias</a>
                
                      <div class="price-box">
                        <p class="price">$149.99</p>
                        <del>$159.99</del>
                      </div>
                
                    </div>
                
                  </div>
                
                  <div class="showcase">
                
                    <a href="https://www.stz.com.br/sapato-social-woche-detalhe-fivela-preto-5192449-p2782551?srsltid=AfmBOor2a4LpD8Q9IXU3sINY5tHTRDzuphXXozPzUY8rzy04VcZzaly0" class="showcase-img-box">
                      <img src="./assets/images/products/Sapato Social Woche Detalhe Fivela Preto.jpg" alt="better basics french terry sweatshorts" class="showcase-img"
                        width="70">
                    </a>
                
                    <div class="showcase-content">
                
                      <a href="https://www.stz.com.br/sapato-social-woche-detalhe-fivela-preto-5192449-p2782551?srsltid=AfmBOor2a4LpD8Q9IXU3sINY5tHTRDzuphXXozPzUY8rzy04VcZzaly0">
                        <h4 class="showcase-title">Sapato Social Woche Detalhe Fivela Preto</h4>
                      </a>
                
                      <a href="#" class="showcase-category">sapato social</a>
                
                      <div class="price-box">
                        <p class="price">$103.99</p>
                        <del>$129.99</del>
                      </div>
                
                    </div>
                
                  </div>
                
                </div>

              </div>

            </div>

            <div class="product-showcase">
            
              <h2 class="title">Tendências</h2>
            
              <div class="showcase-wrapper  has-scrollbar">
            
                <div class="showcase-container">
            
                  <div class="showcase">
            
                    <a href="https://loja.cruzeiro.com.br/p/chuteira-campo-adidas-predator-accuracy-p4-sock-unissex-azul-FB8-8723-028?srsltid=AfmBOoouj9hDZEuAfbMAYgTgPs0RhE0j0mGacX3lQ0sWsSb7KXWCIWPk" class="showcase-img-box">
                      <img src="./assets/images/products/Chuteira Campo Adidas Predator Accuracy P4 Sock Unissex.jpg" alt="running & trekking shoes - white" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://loja.cruzeiro.com.br/p/chuteira-campo-adidas-predator-accuracy-p4-sock-unissex-azul-FB8-8723-028?srsltid=AfmBOoouj9hDZEuAfbMAYgTgPs0RhE0j0mGacX3lQ0sWsSb7KXWCIWPk">
                        <h4 class="showcase-title">Chuteira Campo Adidas Predator Accuracy P4 Sock Unissex</h4>
                      </a>

                      <a href="#" class="showcase-category">chuteiras</a>

                      <div class="price-box">
                        <p class="price">$209.99</p>
                        <del>$449.99</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="https://www.b2online.com.br/chuteira-futsal-adidas-rabisco-junior-laranja---preto?srsltid=AfmBOoo7ih_lQxJVfKVaojOgoiG-9C2gXN_tyI5Tcre0n6Zst16bYiPV" class="showcase-img-box">
                      <img src="./assets/images/products/Chuteira Futsal Adidas Rabisco Junior LaranjaPreto.jpg" alt="trekking & running shoes - black" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://www.b2online.com.br/chuteira-futsal-adidas-rabisco-junior-laranja---preto?srsltid=AfmBOoo7ih_lQxJVfKVaojOgoiG-9C2gXN_tyI5Tcre0n6Zst16bYiPV">
                        <h4 class="showcase-title">Chuteira Futsal Adidas Rabisco Junior LaranjaPreto</h4>
                      </a>

                      <a href="#" class="showcase-category">chuteiras</a>

                      <div class="price-box">
                        <p class="price">$189.90</p>
                        <del>$199.90</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="https://www.esportelegal.com.br/produto/chinelo-olympikus-melbourne-unissex-120748" class="showcase-img-box">
                      <img src="./assets/images/products/Chinelo Olympikus Melbourne Unissex.jpg" alt="womens party wear shoes" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://www.esportelegal.com.br/produto/chinelo-olympikus-melbourne-unissex-120748">
                        <h4 class="showcase-title">Chinelo Olympikus Melbourne Unissex</h4>
                      </a>
            
                      <a href="#" class="showcase-category">chinelos</a>
            
                      <div class="price-box">
                        <p class="price">$129.90</p>
                        <del>$139.90</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="https://bergallycom.mercadoshops.com.br/MLB-1608597400-bota-botina-seguranca-do-trabalho-100-couro-c-ca-frentista-_JM" class="showcase-img-box">
                      <img src="./assets/images/products/Bota Botina Segurança Do Trabalho Couro C Ca Frentista.jpg" alt="sports claw women's shoes" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://bergallycom.mercadoshops.com.br/MLB-1608597400-bota-botina-seguranca-do-trabalho-100-couro-c-ca-frentista-_JM">
                        <h4 class="showcase-title">Bota Botina Segurança Do Trabalho Couro C Ca Frentista</h4>
                      </a>
            
                      <a href="#" class="showcase-category">EPI-s</a>
            
                      <div class="price-box">
                        <p class="price">$78.99</p>
                        <del>$88.99</del>
                      </div>
            
                    </div>
            
                  </div>
            
                </div>
            
                <div class="showcase-container">
            
                  <div class="showcase">
            
                    <a href="https://www.karinacalcados.com.br/sandalia-masculina-dakar-ii-marrom-cartago-12280-ax460" class="showcase-img-box">
                      <img src="./assets/images/products/Sandalia Cartago 12280 Dakar II, Marrom, 4344.jpg" alt="air tekking shoes - white" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://www.karinacalcados.com.br/sandalia-masculina-dakar-ii-marrom-cartago-12280-ax460">
                        <h4 class="showcase-title">Sandália Cartago 12280 Dakar II, Marrom, 43/44</h4>
                      </a>
            
                      <a href="#" class="showcase-category">sandálias</a>
            
                      <div class="price-box">
                        <p class="price">$79.99</p>
                        <del>$89.99</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="https://www.lojawolfpack.com.br/tenis-vans-old-skool-color-theory-golden-brown" class="showcase-img-box">
                      <img src="./assets/images/products/Tênis Vans Old Skool Color Theory Golden Brown.jpg" alt="Boot With Suede Detail" class="showcase-img" width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://www.lojawolfpack.com.br/tenis-vans-old-skool-color-theory-golden-brown">
                        <h4 class="showcase-title">Tênis Vans Old Skool Color Theory Golden Brown</h4>
                      </a>
            
                      <a href="#" class="showcase-category">tênis</a>
            
                      <div class="price-box">
                        <p class="price">$399.99</p>
                        <del>$409.99</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="https://www.sandalo.com.br/sapato-social-sandalo-taylor-cadarco-preto-sd004-preto?srsltid=AfmBOoop7nWMkCTDohg4_cNW21l0MsU0fMZrPWX7rvxPOKKlV03TxCHT" class="showcase-img-box">
                      <img src="./assets/images/products/Sapato Social Sândalo Taylor Cadarço Preto.jpg" alt="men's leather formal wear shoes" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://www.sandalo.com.br/sapato-social-sandalo-taylor-cadarco-preto-sd004-preto?srsltid=AfmBOoop7nWMkCTDohg4_cNW21l0MsU0fMZrPWX7rvxPOKKlV03TxCHT">
                        <h4 class="showcase-title">Sapato Social Sândalo Taylor Cadarço Preto</h4>
                      </a>
            
                      <a href="#" class="showcase-category">sapato social</a>
            
                      <div class="price-box">
                        <p class="price">$399.90</p>
                        <del>$439.90</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="https://shopee.com.br/product/314066583/5656248894?gads_t_sig=VTJGc2RHVmtYMTlxTFVSVVRrdENkWVp3RFo3Mkw5czd4Z0hzdEF1WVFia2NwMFFaaDN5UG81cTZ2NGtsSi9GcGRMc1A2UEczeTRoaW5LYWZGUi9UUk43akZuWFpySGlUV0p3OWkvM3dka0M1UE03Q0xDbjJOL0JhUzV3TjhROGM" class="showcase-img-box">
                      <img src="./assets/images/products/Sapato Social Masculino 803 Cores Diversas Estilo Italiano Bico Quadrado Casual Casamento.jpg" alt="casual men's brown shoes" class="showcase-img" width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="https://shopee.com.br/product/314066583/5656248894?gads_t_sig=VTJGc2RHVmtYMTlxTFVSVVRrdENkWVp3RFo3Mkw5czd4Z0hzdEF1WVFia2NwMFFaaDN5UG81cTZ2NGtsSi9GcGRMc1A2UEczeTRoaW5LYWZGUi9UUk43akZuWFpySGlUV0p3OWkvM3dka0M1UE03Q0xDbjJOL0JhUzV3TjhROGM">
                        <h4 class="showcase-title">Sapato Social Masculino 803 Cores Diversas Estilo Italiano Bico Quadrado Casual Casamento</h4>
                      </a>
            
                      <a href="#" class="showcase-category">sapato social</a>
            
                      <div class="price-box">
                        <p class="price">$79.90</p>
                        <del>$109.90</del>
                      </div>
            
                    </div>
            
                  </div>
            
                </div>
            
              </div>
            
            </div>

            <div class="product-showcase">
            
              <h2 class="title">Os principais avaliados</h2>
            
              <div class="showcase-wrapper  has-scrollbar">
            
                <div class="showcase-container">
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Tenis Bota Jordan Branca com Vermelha Botinha Cano Alto Feminina e Masculina.jpg" alt="pocket watch leather pouch" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Tenis Bota Jordan Branca com Vermelha Botinha Cano Alto Feminina e Masculina</h4>
                      </a>
            
                      <a href="#" class="showcase-category">tênis</a>
            
                      <div class="price-box">
                        <p class="price">$64.00</p>
                        <del>$72.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Sapato de Segurança Fortline SER2002 - Sapato Fortline Bidensidade.jpg" alt="silver deer heart necklace" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Sapato de Segurança Fortline SER2002 - Sapato Fortline Bidensidade</h4>
                      </a>
            
                      <a href="#" class="showcase-category">EPI-s</a>
            
                      <div class="price-box">
                        <p class="price">$54.00</p>
                        <del>$40.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Chinelo Ipanema Maxi Glow em Glitter 27000 3340.jpg" alt="titan 100 ml womens perfume" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Chinelo Ipanema Maxi Glow em Glitter 27000 3340</h4>
                      </a>
            
                      <a href="#" class="showcase-category">chinelos</a>
            
                      <div class="price-box">
                        <p class="price">$42.00</p>
                        <del>$30.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Chinelo Slide Ipanema Disney Stitch Infantil.jpg" alt="men's leather reversible belt" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Chinelo Slide Ipanema Disney Stitch Infantil</h4>
                      </a>

                      <a href="#" class="showcase-category">chinelos</a>

                      <div class="price-box">
                        <p class="price">$34.00</p>
                        <del>$20.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                </div>
            
                <div class="showcase-container">
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Chinelo Havaianas Logomania Marvel Branco.jpg" alt="platinum zircon classic ring" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Chinelo Havaianas Logomania Marvel Branco</h4>
                      </a>
            
                      <a href="#" class="showcase-category">chinelos</a>
            
                      <div class="price-box">
                        <p class="price">$49.90</p>
                        <del>$54.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Sapato Masculino Oxford em Couro Confort Preto - Cód 41089.jpg" alt="smart watche vital plus" class="showcase-img" width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Sapato Masculino Porto free Oxford em Couro Confort Preto - Cód 41089</h4>
                      </a>
            
                      <a href="#" class="showcase-category">oxfords</a>
            
                      <div class="price-box">
                        <p class="price">$56.00</p>
                        <del>$58.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Tênis Converse All Star Cano Alto - Vermelho - Chuck Taylor - Botinha - Nolan Calçados.jpg" alt="shampoo conditioner packs" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Tênis Converse All Star Cano Alto - Vermelho - Chuck Taylor - Botinha - Nolan Calçados</h4>
                      </a>
            
                      <a href="#" class="showcase-category">tênis</a>
            
                      <div class="price-box">
                        <p class="price">$85.00</p>
                        <del>$90.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                  <div class="showcase">
            
                    <a href="#" class="showcase-img-box">
                      <img src="./assets/images/products/Sandália Papete Moleca Flatform Feminina.jpg" alt="rose gold peacock earrings" class="showcase-img"
                        width="70">
                    </a>
            
                    <div class="showcase-content">
            
                      <a href="#">
                        <h4 class="showcase-title">Sandália Papete Moleca Flatform Feminina</h4>
                      </a>
            
                      <a href="#" class="showcase-category">sandália</a>
            
                      <div class="price-box">
                        <p class="price">$32.00</p>
                        <del>$42.00</del>
                      </div>
            
                    </div>
            
                  </div>
            
                </div>
            
              </div>
            
            </div>

          </div>



          <!--
            - PRODUCT FEATURED
          -->

          <div class="product-featured">

            <h2 class="title">Ideal para o dia</h2>

            <div class="showcase-wrapper has-scrollbar">

              <div class="showcase-container">

                <div class="showcase">
                  
                  <div class="showcase-banner">
                    <img src="./assets/images/products/Tênis Converse All Star Cano Alto - Vermelho - Chuck Taylor - Botinha - Nolan Calçados.jpg" alt="shampoo, conditioner & facewash packs" class="showcase-img">
                  </div>

                  <div class="showcase-content">
                    
                    <div class="showcase-rating">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star-outline"></ion-icon>
                      <ion-icon name="star-outline"></ion-icon>
                    </div>

                    <a href="#">
                      <h3 class="showcase-title">Tênis Converse All Star Cano Alto - Vermelho - Chuck Taylor - Botinha - Nolan Calçados</h3>
                    </a>

                    <p class="showcase-desc">
                      Quem não gostaria de usar um All star no seu dia a dia? Temos aqui um modelo de cano alto para você.
                    </p>

                    <div class="price-box">
                      <p class="price">$85.00</p>

                      <del>$90.00</del>
                    </div>

                    <button class="add-cart-btn">Adicionar ao carrinho
                    </button>

                    <div class="showcase-status">
                      <div class="wrapper">
                        <p>
                          já vendido: <b>20</b>
                        </p>

                        <p>
                          disponível: <b>40</b>
                        </p>
                      </div>

                      <div class="showcase-status-bar"></div>
                    </div>

                    <div class="countdown-box">

                      <p class="countdown-desc">
                        Se apresse! A oferta termina em:
                      </p>

                      <div class="countdown">

                        <div class="countdown-content">

                          <p class="display-number">360</p>

                          <p class="display-text">Dias</p>

                        </div>

                        <div class="countdown-content">
                          <p class="display-number">24</p>
                          <p class="display-text">Horas</p>
                        </div>

                        <div class="countdown-content">
                          <p class="display-number">59</p>
                          <p class="display-text">Min</p>
                        </div>

                        <div class="countdown-content">
                          <p class="display-number">00</p>
                          <p class="display-text">Seg</p>
                        </div>

                      </div>

                    </div>

                  </div>

                </div>

              </div>

              <div class="showcase-container">
              
                <div class="showcase">
              
                  <div class="showcase-banner">
                    <img src="./assets/images/products/Chuck Taylor All Star Vermelho.jpg" alt="Rose Gold diamonds Earring" class="showcase-img">
                  </div>
              
                  <div class="showcase-content">
              
                    <div class="showcase-rating">
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star"></ion-icon>
                      <ion-icon name="star-outline"></ion-icon>
                      <ion-icon name="star-outline"></ion-icon>
                    </div>
              
                    <h3 class="showcase-title">
                      <a href="#" class="showcase-title">Chuck Taylor All Star Vermelho</a>
                    </h3>
              
                    <p class="showcase-desc">
                      Quem não gostaria de usar um All star no seu dia a dia? Temos aqui um modelo para você.
                    </p>
              
                    <div class="price-box">
                      <p class="price">$70.00</p>
                      <del>$79.99</del>
                    </div>
              
                    <button class="add-cart-btn">Adicionar ao carrinho</button>
              
                    <div class="showcase-status">
                      <div class="wrapper">
                        <p> já vendido: <b>15</b> </p>
              
                        <p> disponível: <b>40</b> </p>
                      </div>
              
                      <div class="showcase-status-bar"></div>
                    </div>
              
                    <div class="countdown-box">
              
                      <p class="countdown-desc">Se apresse! A oferta termina em</p>
              
                      <div class="countdown">
                        <div class="countdown-content">
                          <p class="display-number">360</p>
                          <p class="display-text">Dias</p>
                        </div>
              
                        <div class="countdown-content">
                          <p class="display-number">24</p>
                          <p class="display-text">Horas</p>
                        </div>
              
                        <div class="countdown-content">
                          <p class="display-number">59</p>
                          <p class="display-text">Min</p>
                        </div>
              
                        <div class="countdown-content">
                          <p class="display-number">00</p>
                          <p class="display-text">Seg</p>
                        </div>
                      </div>
              
                    </div>
              
                  </div>
              
                </div>
              
              </div>

            </div>

          </div>



          <!--
            - PRODUCT GRID
          -->

          <div class="product-main">

            <h2 class="title">Novos calçados</h2>

            <div class="product-grid">

              <div class="showcase">

                <div class="showcase-banner">

                  <img src="./assets/images/products/Sandália Feminina Vizzano Salto Geométrico Preto - 38.jpg" alt="Mens Winter Leathers Jackets" width="300" class="product-img default">
                  <img src="./assets/images/products/Sandália Feminina Vizzano Salto Geométrico Preto - 38 - 2.jpg" alt="Mens Winter Leathers Jackets" width="300" class="product-img hover">

                  <p class="showcase-badge">15%</p>

                  <div class="showcase-actions">

                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>

                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>

                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>

                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>

                  </div>

                </div>

                <div class="showcase-content">

                  <a href="#" class="showcase-category">sandálias</a>

                  <a href="https://www.layneshoes.com.br/categoria-feminino-saltos/sandalia-vizzano-salto-geometrico-tira-com-fivela-preto?srsltid=AfmBOorkMwMN-5zw_MauraGsgktj8ahnmWzcCvJNzNU3Q9IqWprz8Sep&variant_id=87160">
                    <h3 class="showcase-title">Sandália Feminina Vizzano Salto Geométrico Preto - 38</h3>
                  </a>

                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>

                  <div class="price-box">
                    <p class="price">$149.99</p>
                    <del>$159.99</del>
                  </div>

                </div>

              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Mocassim Masculino Fretz em Couro Senna Tan.jpg" alt="Pure Garment Dyed Cotton Shirt" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Mocassim Masculino Fretz em Couro Senna Tan - 2.jpg" alt="Pure Garment Dyed Cotton Shirt" class="product-img hover"
                    width="300">
              
                  <p class="showcase-badge angle black">oferta</p>
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">mocassins</a>
              
                  <h3>
                    <a href="#" class="showcase-title">Mocassim Andacco Masculino Fretz em Couro Senna Tan</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$56.00</p>
                    <del>$60.00</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Tênis Nike Renew Run 3 Feminino - Vermelho.jpg" alt="MEN Yarn Fleece Full-Zip Jacket" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Tênis Nike Renew Run 3 Feminino - Vermelho - 2.jpg" alt="MEN Yarn Fleece Full-Zip Jacket" class="product-img hover"
                    width="300">
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">tênis</a>
              
                  <h3>
                    <a href="https://www.spazziojeans.com.br/tenis-nike-renew-run-3-feminino-rosa-e-vermelho?&sort=p.date_added&order=DESC&page=62" class="showcase-title">Tênis Nike Renew Run 3 Feminino - Vermelho</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$449.94</p>
                    <del>$749.90</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Sapatilha Moleca 5027.1407 - Preto - 36.jpg" alt="Black Floral Wrap Midi Skirt" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Sapatilha Moleca 5027.1407 - Preto - 36 - 2.jpg" alt="Black Floral Wrap Midi Skirt" class="product-img hover"
                    width="300">
              
                  <p class="showcase-badge angle pink">novo</p>
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">sapatilhas</a>
              
                  <h3>
                    <a href="https://www.magazineluiza.com.br/sapatilha-feminina-moleca-5027-1407-preto/p/gf69fbg25j/md/spth/" class="showcase-title">Sapatilha Moleca 5027.1407 - Preto - 36</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$80.49</p>
                    <del>$90.49</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Sapato Social Masculino 803 Cores Diversas Estilo Italiano Bico Quadrado Casual Casamento.jpg" alt="Casual Men's Brown shoes" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Sapato Social Masculino 803 Azul Estilo Italiano Bico Quadrado Casual Casamento.jpg" alt="Casual Men's Brown shoes" class="product-img hover"
                    width="300">
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">sapato social</a>
              
                  <h3>
                    <a href="https://shopee.com.br/product/314066583/5656248894?gads_t_sig=VTJGc2RHVmtYMTlxTFVSVVRrdENkWVp3RFo3Mkw5czd4Z0hzdEF1WVFia2NwMFFaaDN5UG81cTZ2NGtsSi9GcGRMc1A2UEczeTRoaW5LYWZGUi9UUk43akZuWFpySGlUV0p3OWkvM3dka0M1UE03Q0xDbjJOL0JhUzV3TjhROGM" class="showcase-title">Sapato Social Masculino Schiareli 803 Cores Diversas Estilo Italiano Bico Quadrado Casual Casamento</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$79.90</p>
                    <del>$109.90</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Buy Nike Air Max 90 Men's Shoe.jpg" alt="Pocket Watch Leather Pouch" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Buy Nike Air Max 90 Men's Shoe - 2.jpg" alt="Pocket Watch Leather Pouch" class="product-img hover"
                    width="300">
              
                  <p class="showcase-badge angle black">oferta</p>
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">tênis</a>
              
                  <h3>
                    <a href="#" class="showcase-title">Nike Air Max 90 tênis masculino</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$89.00</p>
                    <del>$92.00</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Sapato Masculino Oxford em Couro Confort Preto - Cód 41089.jpg" alt="Smart watche Vital Plus" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Sapato Masculino Oxford em Couro Confort Preto - Cód 41089 - 2.jpg" alt="Smart watche Vital Plus" class="product-img hover" width="300">
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">oxfords</a>
              
                  <h3>
                    <a href="#" class="showcase-title">Sapato Masculino Porto free Oxford em Couro Confort Preto - Cód 41089</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$56.00</p>
                    <del>$58.00</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Sandália Feminina Rasteirinha Infantil Peep Toe Com Pérola.jpg" alt="Womens Party Wear Shoes" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Sandália Feminina Rasteirinha Infantil Peep Toe Com Pérola - 2.jpg" alt="Womens Party Wear Shoes" class="product-img hover"
                    width="300">
              
                  <p class="showcase-badge angle black">oferta</p>
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">sandálias</a>
              
                  <h3>
                    <a href="#" class="showcase-title">Sandália Feminina Rasteirinha Infantil Peep Toe Com Pérola</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$26.00</p>
                    <del>$30.00</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Sandália Rasteira Sunflower Marfim.jpg" alt="Mens Winter Leathers Jackets" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Sandália Rasteira Sunflower Marfim - 2.jpg" alt="Mens Winter Leathers Jackets" class="product-img hover"
                    width="300">
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">sandálias</a>
              
                  <h3>
                    <a href="https://viamiss.com.br/sandalia-rasteira-strass-dedo-no-marfim-rr1014-163?srsltid=AfmBOoqoNtrH-WFIwdE--YvIGeV7Vo1qWZIGZUO628LoOAS-4E8t2Qpp" class="showcase-title">Sandália Rasteira Sunflower Marfim Via miss</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$129.90</p>
                    <del>$139.90</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Chuteira Futsal Adidas Rabisco Junior LaranjaPreto.jpg" alt="Trekking & Running Shoes - black" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Chuteira Futsal Adidas Rabisco Junior LaranjaPreto - 2.jpg" alt="Trekking & Running Shoes - black" class="product-img hover"
                    width="300">
              
                  <p class="showcase-badge angle black">oferta</p>
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">chuteiras</a>
              
                  <h3>
                    <a href="https://www.b2online.com.br/chuteira-futsal-adidas-rabisco-junior-laranja---preto?srsltid=AfmBOoo7ih_lQxJVfKVaojOgoiG-9C2gXN_tyI5Tcre0n6Zst16bYiPV" class="showcase-title">Chuteira Futsal Adidas Rabisco Junior Laranja e Preto</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$189.90</p>
                    <del>$199.90</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Tenis Bota Jordan Branca com Vermelha Botinha Cano Alto Feminina e Masculina.jpg" alt="Men's Leather Formal Wear shoes" class="product-img default"
                    width="300">
                  <img src="./assets/images/products/Tenis Bota Jordan Branca com Vermelha Botinha Cano Alto Feminina e Masculina - 2.jpg" alt="Men's Leather Formal Wear shoes" class="product-img hover"
                    width="300">
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">tênis</a>
              
                  <h3>
                    <a href="#" class="showcase-title">Tenis Bota Jordan Branca com Vermelha Botinha Cano Alto Feminina e Masculina</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$64.00</p>
                    <del>$72.00</del>
                  </div>
              
                </div>
              
              </div>

              <div class="showcase">
              
                <div class="showcase-banner">
                  <img src="./assets/images/products/Scarpin Couro Marrom Salto Alto Cecconello 2130008-2, 39, Marrom.jpg" alt="Better Basics French Terry Sweatshorts"
                    class="product-img default" width="300">
                  <img src="./assets/images/products/Scarpin Couro Preto Salto Alto Cecconello 2130008-83, 38, Preto.jpg" alt="Better Basics French Terry Sweatshorts"
                    class="product-img hover" width="300">
              
                  <p class="showcase-badge angle black">oferta</p>
              
                  <div class="showcase-actions">
                    <button class="btn-action">
                      <ion-icon name="heart-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="eye-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="repeat-outline"></ion-icon>
                    </button>
              
                    <button class="btn-action">
                      <ion-icon name="bag-add-outline"></ion-icon>
                    </button>
                  </div>
                </div>
              
                <div class="showcase-content">
                  <a href="#" class="showcase-category">salto alto</a>
              
                  <h3>
                    <a href="#" class="showcase-title">Scarpin Couro Marrom Salto Alto Cecconello 2130008-2, 39</a>
                  </h3>
              
                  <div class="showcase-rating">
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                    <ion-icon name="star-outline"></ion-icon>
                  </div>
              
                  <div class="price-box">
                    <p class="price">$78.00</p>
                    <del>$85.00</del>
                  </div>
              
                </div>
              
              </div>

            </div>

          </div>

        </div>

      </div>

    </div>





    <!--
      - TESTIMONIALS, CTA & SERVICE
    -->

    <div>

      <div class="container">

        <div class="testimonials-box">

          <!--
            - TESTIMONIALS
          -->

          <div class="testimonial">

            <h2 class="title">Depoimentos</h2>

            <div class="testimonial-card">

              <img src="./assets/images/testimonial-1.jpg" alt="alan doe" class="testimonial-banner" width="80" height="80">

              <p class="testimonial-name">Pedro Henrique</p>

              <p class="testimonial-title">Pedro1dog</p>

              <img src="./assets/images/icons/quotes.svg" alt="quotation" class="quotation-img" width="26">

              <p class="testimonial-desc">
                Quando criamos essa empresa, pensamos no publíco em geral, em que cada um queira vir e nos procurar para conseguir o calçado certo para o pé.
              </p>

            </div>

          </div>



          <!--
            - CTA
          -->

          <div class="cta-container">

            <img src="./assets/images/cta-banner.jpg" alt="summer collection" class="cta-banner">

            <a href="#" class="cta-content">

              <p class="discount">25% de disconto</p>

              <h2 class="cta-title">Coleção do verão</h2>

              <p class="cta-text">Começando com $10</p>

              <button class="cta-btn">compre agora</button>

            </a>

          </div>



          <!--
            - SERVICE
          -->

          <div class="service">

            <h2 class="title">Nossos serviços</h2>

            <div class="service-container">

              <a href="#" class="service-item">

                <div class="service-icon">
                  <ion-icon name="boat-outline"></ion-icon>
                </div>

                <div class="service-content">

                  <h3 class="service-title">Entrega internacional</h3>
                  <p class="service-desc">Acima de $100</p>

                </div>

              </a>

              <a href="#" class="service-item">
              
                <div class="service-icon">
                  <ion-icon name="rocket-outline"></ion-icon>
                </div>
              
                <div class="service-content">
              
                  <h3 class="service-title">Entrega rápida</h3>
                  <p class="service-desc">Apenas encomenda BR</p>
              
                </div>
              
              </a>

              <a href="#" class="service-item">
              
                <div class="service-icon">
                  <ion-icon name="call-outline"></ion-icon>
                </div>
              
                <div class="service-content">
              
                  <h3 class="service-title">Melhor suporte online</h3>
                  <p class="service-desc">Horários: 8:00 - 22:00</p>
              
                </div>
              
              </a>

              <a href="#" class="service-item">
              
                <div class="service-icon">
                  <ion-icon name="arrow-undo-outline"></ion-icon>
                </div>
              
                <div class="service-content">
              
                  <h3 class="service-title">Política de devolução</h3>
                  <p class="service-desc">Devolução fácil e grátis</p>
              
                </div>
              
              </a>

              <a href="#" class="service-item">
              
                <div class="service-icon">
                  <ion-icon name="ticket-outline"></ion-icon>
                </div>
              
                <div class="service-content">
              
                  <h3 class="service-title">30% do seu dinheiro devolta</h3>
                  <p class="service-desc">Acima de $100</p>
              
                </div>
              
              </a>

            </div>

          </div>

        </div>

      </div>

    </div>





    <!--
      - BLOG
    -->

    <div class="blog">

      <div class="container">

        <div class="blog-container has-scrollbar">

          <div class="blog-card">

            <a href="#">
              <img src="./assets/images/blog-1.jpg" alt="Clothes Retail KPIs 2021 Guide for Clothes Executives" width="300" class="blog-banner">
            </a>

            <div class="blog-content">

              <a href="#" class="blog-category">Infantil</a>

              <a href="#">
                <h3 class="blog-title">Dicas para o seu pequeno sobre como ter conforto nos pés.</h3>
              </a>

              <p class="blog-meta">
                De <cite>Sr Admin</cite> / <time datetime="2022-04-06">06,Abr, 2022</time>
              </p>

            </div>

          </div>

          <div class="blog-card">
          
            <a href="#">
              <img src="./assets/images/blog-2.jpg" alt="Curbside fashion Trends: How to Win the Pickup Battle."
                class="blog-banner" width="300">
            </a>
          
            <div class="blog-content">
          
              <a href="#" class="blog-category">Formal</a>
          
              <h3>
                <a href="#" class="blog-title">Vai para algum evento e ainda não sabe qual sapato usar? Oferecemos aqui algumas opções que você vai gostar.</a>
              </h3>
          
              <p class="blog-meta">
                De <cite>Sr Robin</cite> / <time datetime="2022-01-18">18, Jan, 2022</time>
              </p>
          
            </div>
          
          </div>

          <div class="blog-card">
          
            <a href="#">
              <img src="./assets/images/blog-3.jpg" alt="EBT vendors: Claim Your Share of SNAP Online Revenue."
                class="blog-banner" width="300">
            </a>
          
            <div class="blog-content">
          
              <a href="#" class="blog-category">Formal</a>
          
              <h3>
                <a href="#" class="blog-title">Temos o que você precisa para usar num casamento.</a>
              </h3>
          
              <p class="blog-meta">
                De <cite>Srs Selsa</cite> / <time datetime="2022-02-10">10, Fev, 2022</time>
              </p>
          
            </div>
          
          </div>

          <div class="blog-card">
          
            <a href="#">
              <img src="./assets/images/blog-4.jpg" alt="Curbside fashion Trends: How to Win the Pickup Battle."
                class="blog-banner" width="300">
            </a>
          
            <div class="blog-content">
          
              <a href="#" class="blog-category">Infantil</a>
          
              <h3>
                <a href="#" class="blog-title">Novidades para as meninas.</a>
              </h3>
          
              <p class="blog-meta">
                De <cite>Srs Pawar</cite> / <time datetime="2022-03-15">15, Mar, 2022</time>
              </p>
          
            </div>
          
          </div>

        </div>

      </div>

    </div>

  </main>





  <!--
    - FOOTER
  -->

  <footer>

    <div class="footer-category">

      <div class="container">

        <h2 class="footer-category-title">Marca diretório</h2>

        <div class="footer-category-box">

          <h3 class="category-box-title">Calçados :</h3>

          <a href="#" class="footer-category-link">bota</a>
          <a href="#" class="footer-category-link">cadarço</a>
          <a href="#" class="footer-category-link">chinelo</a>
          <a href="#" class="footer-category-link">chuteira</a>
          <a href="#" class="footer-category-link">EPI-s</a>
          <a href="#" class="footer-category-link">meia</a>
          <a href="#" class="footer-category-link">mocassin</a>
          <a href="#" class="footer-category-link">oxford</a>
          <a href="#" class="footer-category-link">palmilha</a>
          <a href="#" class="footer-category-link">rasteirinha</a>
          <a href="#" class="footer-category-link">salto alto</a>
          <a href="#" class="footer-category-link">sandália</a>
          <a href="#" class="footer-category-link">sapatilha</a>
          <a href="#" class="footer-category-link">tênis</a>

        </div>

        <div class="footer-category-box">
          <h3 class="category-box-title">Estilo :</h3>
        
          <a href="#" class="footer-category-link">Formal</a>
          <a href="#" class="footer-category-link">Infantil</a>
          <a href="#" class="footer-category-link">Esporte</a>
          <a href="#" class="footer-category-link">Escolar</a>
          <a href="#" class="footer-category-link">Praia</a>
          <a href="#" class="footer-category-link">Masculino</a>
          <a href="#" class="footer-category-link">Feminino</a>
        </div>

        <div class="footer-category-box">
          <h3 class="category-box-title">Acessórios :</h3>
        
          <a href="#" class="footer-category-link">cadarço</a>
          <a href="#" class="footer-category-link">meia</a>
          <a href="#" class="footer-category-link">palmilha</a>
          <a href="#" class="footer-category-link">calçadeiras</a>
          <a href="#" class="footer-category-link">calcanheira</a>
        </div>

        <div class="footer-category-box">
          <h3 class="category-box-title">Marcas :</h3>
        
          <a href="#" class="footer-category-link">Nike</a>
          <a href="#" class="footer-category-link">Havaianas</a>
          <a href="#" class="footer-category-link">Ipanema</a>
          <a href="#" class="footer-category-link">Rider</a>
          <a href="#" class="footer-category-link">Olympikus</a>
          <a href="#" class="footer-category-link">All star</a>
          <a href="#" class="footer-category-link">Adidas</a>
          <a href="#" class="footer-category-link">Lupo</a>
          <a href="#" class="footer-category-link">Andacco</a>
          <a href="#" class="footer-category-link">Pé relax</a>
          <a href="#" class="footer-category-link">Cartago</a>
          <a href="#" class="footer-category-link">Dakota</a>
          <a href="#" class="footer-category-link">Menina fashion</a>
          <a href="#" class="footer-category-link">Vizzano</a>
          <a href="#" class="footer-category-link">Moleca</a>
          <a href="#" class="footer-category-link">Via miss</a>
          <a href="#" class="footer-category-link">Fortline</a>
          <a href="#" class="footer-category-link">Ferracini</a>
          <a href="#" class="footer-category-link">Porto free</a>
          <a href="#" class="footer-category-link">Schiareli</a>
          <a href="#" class="footer-category-link">Sândalo</a>
          <a href="#" class="footer-category-link">Woche</a>
          <a href="#" class="footer-category-link">Cecconello</a>
          <a href="#" class="footer-category-link">Vans</a>
          <a href="#" class="footer-category-link">Umbro</a>
          <a href="#" class="footer-category-link">Cronos</a>
          <a href="#" class="footer-category-link">Art nobre</a>
          <a href="#" class="footer-category-link">Hugo boss</a>
          <a href="#" class="footer-category-link">Gats</a>
          <a href="#" class="footer-category-link">Beira rio</a>
        </div>

      </div>

    </div>

    <div class="footer-nav">

      <div class="container">

        <ul class="footer-nav-list">

          <li class="footer-nav-item">
            <h2 class="nav-title">Categorias populares</h2>
          </li>

          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Masculino</a>
          </li>

          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Feminino</a>
          </li>

          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Marcas</a>
          </li>

          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Acessórios</a>
          </li>

          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Casual</a>
          </li>

        </ul>

        <ul class="footer-nav-list">
        
          <li class="footer-nav-item">
            <h2 class="nav-title">Produtos</h2>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Preços baixos</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Novos produtos</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Melhores vendas</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Nos contate</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Mapa do site</a>
          </li>
        
        </ul>

        <ul class="footer-nav-list">
        
          <li class="footer-nav-item">
            <h2 class="nav-title">Nossa companhia</h2>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Entrega</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Notícias legais</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Termos e condições</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Sobre nós</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Pagamento seguro</a>
          </li>
        
        </ul>

        <ul class="footer-nav-list">
        
          <li class="footer-nav-item">
            <h2 class="nav-title">Serviços</h2>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Preços baixos</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Novos produtos</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Melhores vendas</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Nos contate</a>
          </li>
        
          <li class="footer-nav-item">
            <a href="#" class="footer-nav-link">Mapa do site</a>
          </li>
        
        </ul>

        <ul class="footer-nav-list">

          <li class="footer-nav-item">
            <h2 class="nav-title">Contato</h2>
          </li>

          <li class="footer-nav-item flex">
            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>

            <address class="content">
              419 Estado 414 Rte
              Barragens do castor, Nova Iorque(NI), 14812, EUA
            </address>
          </li>

          <li class="footer-nav-item flex">
            <div class="icon-box">
              <ion-icon name="call-outline"></ion-icon>
            </div>

            <a href="tel:+607936-8058" class="footer-nav-link">(607) 936-8058</a>
          </li>

          <li class="footer-nav-item flex">
            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>

            <a href="mailto:example@gmail.com" class="footer-nav-link">exemplo@gmail.com</a>
          </li>

        </ul>

        <ul class="footer-nav-list">

          <li class="footer-nav-item">
            <h2 class="nav-title">Follow Us</h2>
          </li>

          <li>
            <ul class="social-link">

              <li class="footer-nav-item">
                <a href="#" class="footer-nav-link">
                  <ion-icon name="logo-facebook"></ion-icon>
                </a>
              </li>

              <li class="footer-nav-item">
                <a href="#" class="footer-nav-link">
                  <ion-icon name="logo-twitter"></ion-icon>
                </a>
              </li>

              <li class="footer-nav-item">
                <a href="#" class="footer-nav-link">
                  <ion-icon name="logo-linkedin"></ion-icon>
                </a>
              </li>

              <li class="footer-nav-item">
                <a href="#" class="footer-nav-link">
                  <ion-icon name="logo-instagram"></ion-icon>
                </a>
              </li>

            </ul>
          </li>

        </ul>

      </div>

    </div>

    <div class="footer-bottom">

      <div class="container">

        <img src="./assets/images/payment.png" alt="payment method" class="payment-img">

        <p class="copyright">
          Copyright &copy; <a href="#">Teacher Web</a> all rights reserved.
        </p>

      </div>

    </div>

  </footer>






  <!--
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
