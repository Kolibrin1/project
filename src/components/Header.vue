<template>
    <header class="header">
        <div class="header-container o-container">
            <div class="header-mmenu">
                <span></span>
            </div>
            <div class="header-menu-wrapper">
                <ul class="header-menu o-container">
                    <div class="header-logo o-container">
                        <a href="#">
                            <img src="../assets/img/drupal-coder.svg" alt="drupal-icon">
                        </a>
                    </div>
                    <li class="header-menu-link" id="supp"><a href="#support">Поддержка сайтов</a></li>
                    <li class="header-menu-link" id="rate"><a href="#plans">Тарифы</a></li>
                    <li class="header-menu-link" id="works"><a href="#cases">Наши работы</a></li>
                    <li class="header-menu-link" id="rev"><a href="#reviews">Отзывы</a></li>
                    <li class="header-menu-link" id="contacts"><a href="#form">Контакты</a></li>
                    <ul class="header-contacts">
                        <li class="header-phone"><a href="tel:88002222673">8 800 222-26-73</a></li>
                        <li class="header-lang">
                            <a href="#">RU</a>
                            <ul>
                                <li><a href="#">EN</a></li>
                                <li><a href="#">CN</a></li>
                            </ul>
                        </li>
                        <img class="header-lang-arrow" src="../assets/img/header/arrow-lang.svg" alt="">
                    </ul>
                </ul>
            </div>

            <div class="header-content">
                <div class="header-txt o-container">
                    <h1 class="header-content-title">Поддержка сайтов на Drupal</h1>
                    <p class="header-content-text">Сопровождение и поддержка сайтов на CMS Drupal любых версий и
                        запущенности</p>
                    <a href="#plans" class="header-btn">ТАРИФЫ</a>

                </div>

                <div class="header-achievement">

                    <div class="header-achievement-item" style="padding-top: 0px">
                        <span style="font-size: 48px;">#1</span>
                        <p>
                            Drupal-разработчик в России по версии Рейтинга Рунета
                        </p>

                        <img src="../assets/img/header/cup.png" alt="" class="header-img-cup">
                    </div>
                    <li class="header-achievement-item">
                        <span>3+</span>
                        <p>
                            средний опыт специалистов более
                            3 лет
                        </p>

                    </li>
                    <div class="header-achievement-item">
                        <span>14</span>
                        <p>
                            лет опыта в сфере Drupal
                        </p>

                    </div>
                    <div class="header-achievement-item">
                        <span>200+</span>
                        <p>
                            модулей и тем
                            в формате DrupalGive
                        </p>

                    </div>
                    <div class="header-achievement-item">
                        <span>35 000</span>
                        <p>
                            часов поддержки сайтов на Drupal
                        </p>

                    </div>
                    <div class="header-achievement-item">
                        <span>200+</span>
                        <p>
                            Проектов
                            на поддержке
                        </p>

                    </div>

                </div>
            </div>
        </div>
        <div class="header-druplicon">
            <img src="../assets/img/header/druplicon.svg">
        </div>
        <video autoplay muted loop class="header-video">
            <source src="../assets/img/header/video.mp4" type="video/mp4">
        </video>
    </header>
</template>
<script>
    export default
    {
        name: 'Header'
    }
</script>

<style scoped>
    .header {
    width: 100%;
    height: 650px;
    color: #FFFFFF;
}

.header-container {
    max-width: 1460px;
    padding: 0 10px;
    margin: 0 auto;
}

/* Логотип и меню в шапке */

.header-logo {
    padding-right: 185px;
    z-index: 4;
}


.header-menu {
    display: flex;
    padding: 37px 0 0 0;
    justify-content: center;
    align-items: center;
    font-family: Ubuntu;
    font-weight: 500;
    font-size: 12px;
    line-height: 10px;
    letter-spacing: 0.06em;
    text-transform: uppercase;
}

.header-menu-link {
    cursor: pointer;
    margin-right: 32px;
    z-index: 5;
}

/* анимации */

#supp:after,
#rate:after,
#works:after,
#rev:after,
#contacts:after {
    display: none;
    margin-top: 5px;
    color: #FFFFFF;
    position: absolute;
    content: "";
    height: 3px;
    background-color: #F14D34;
    transition: width 0.5s ease;
    z-index: 4;
    width: 100%;
}

#supp:after {
    width: 141px;
}

#rate:after,
#rev:after {
    width: 56px;
}

#works:after {
    width: 98px;
}

#contacts:after {
    width: 71px;
}

#supp:hover:after,
#works:hover:after,
#rev:hover:after,
#contacts:hover:after,
#rate:hover:after {
    display: block;
    transition: 0.4s;
    color: #FFFFFF;
}

/* Телефон */

.header-contacts {
    display: flex;
    align-items: center;
    z-index: 5;
}

.header-phone {
    z-index: 2;
    margin-left: 70px;
    font-size: 18px;
    line-height: 14px;
}

/* Смена языка */

.header-lang {
    z-index: 4;
    padding-left: 38px;
    font-weight: bold;
    font-size: 14px;
    line-height: 14px;
    position: relative;
}

.header-lang-arrow {
    z-index: 4;
    padding-left: 10px;
}

.header-lang ul {
    position: absolute;
    top: 10px;
    padding-top: 15px;
    display: none;
    min-width: 60px;
}

.header-lang ul li {
    background: #F14D34;
}

.header-lang ul li a {
    padding: 10px;
    text-transform: none;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 14px;

}

.header-lang:hover>ul {
    display: block;
    z-index: 4;
}



/* Основная информация хедера  */

.header-txt {
    width: 750px;
    margin-left: 100px;
}

.header-content-title {
    max-width: 475px;
    margin-bottom: 15px;
    font-weight: bold;
    font-size: 52px;
    line-height: 60px;
}

.header-content-text {
    max-width: 480px;
    font-size: 18px;
    line-height: 28px;
    margin-bottom: 55px;
    opacity: 0.8;
}


.header-btn {

    display: block;
    margin-top: 55px;
    cursor: pointer;
    width: 220px;
    height: 60px;
    border: 2px solid #F14D34;
    border-radius: 5px;
    display: flex;
    letter-spacing: 0.06em;
    justify-content: center;
    align-items: center;
    font-size: 12px;
    text-transform: uppercase;
}

.header-btn:hover {
    background-color: #F14D34;
    transition: 0.3s;
}

/*  Достижения компании */

.header-img-cup {
    position: absolute;
    width: 59px;
    height: 58px;
    left: 50px;
    top: 204px;
}

.header-content {
    color: white;
    position: relative;
    z-index: 3;
    display: flex;
    align-items: center;
    height: 100%;
    height: 562px;
}

.header-achievement {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    padding: 153px 60px 154px 97px;
}

.header-achievement .header-achievement-item {
    position: relative;
    height: 92px;
    width: 135px;
    margin: 70px 70px 50px 0px;
    padding-top: 20px;
}

.header-achievement .header-achievement-item span {
    font-size: 24px;
    font-weight: bold;
}

.header-achievement .header-achievement-item p {
    opacity: 0.8;
    font-size: 12px;
    line-height: 15px;
    margin-top: 8px;
}

.header-achievement .header-achievement-item img {
    position: absolute;
    top: -10px;
}

.header-achievement .header-achievement-item::before {
    content: "";
    display: block;
    position: absolute;
    left: -11px;
    width: 3px;
    background-color: #F14D34;
    height: 80px;
}

.header-achievement .header-achievement-item :first-child:before {
    content: "";
    display: block;
    position: absolute;
    left: -11px;
    top: 5px;
    width: 3px;
    background-color: #F14D34;
    height: 100px;
}

/*  Фон хедера  */

.header-video {
    width: 100%;
    max-height: 650px;
    height: 100%;
    filter: brightness(25%);
    position: absolute;
    object-fit: cover;
    top: 0;
    left: 0;
}
.header-druplicon {
    position: absolute;

    left: 0px;
    top: 0px;
    z-index: 2;

    background: linear-gradient(300deg, rgba(0, 0, 0, 0.548));
    transform: rotate(-1deg);
}
@media screen and (max-width: 575px) {
  
  /* ШАПКА САЙТА */

  .header {
    text-align: center;
  }

  .header-container {
    width: 100%;
    flex-direction: column;
    padding: 0px 20px;
  }
 
  .header-druplicon img {
    height: 400px;
    width: 400px;
  }

  .header-video {
    width: 100%;
    min-height: 800px;
  }
    
     /* mmenu в шапке */

  .header-mmenu {
    right: 0;
    bottom: 0;
    margin: 15px;
    position: fixed;
    display: block;
    width: 30px;
    height: 18px;
    z-index: 10;
  }

  .header-mmenu span {
    position: absolute;
    background-color: white;
    width: 100%;
    height: 2px;
    top: 8px;
    left: 0;
    opacity: 0.5;
  }

  .header-mmenu::before,
  .header-mmenu::after {
    content: "";
    background-color: white;
    position: absolute;
    width: 100%;
    height: 2px;
    left: 0;
    opacity: 0.5;
  }

  .header-mmenu::before {
    right: 0;
  }

  .header-mmenu::after {
    bottom: 0;
  }
    
    /* menu шапки */

  .header-menu {
    position: fixed;
    background-color: #333;
    bottom: 0;
    left: 0;
    z-index: 15;
    height: 48px;
    justify-content: space-between;
    padding: 0px 10px;
  }

  .header-container .header-menu li {
    width: 100%;
    border-bottom: 1px solid black;
    padding: 8px 20px;
    height: 39px;
    z-index: 10;
  }

  .header-container .header-menu li:first-child a {
    color: #F14D34;
  }

  .header-menu-wrapper {
    position: fixed;
    width: 100%;
    height: 620px;
    bottom: -200%;
    left: 0;
    background-color: #333;
    z-index: 4;
    transition: 0.3s;
  }

  .header-menu-wrapper::before {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background-color: #333;
    z-index: 10;
    border-top: 1px solid black;
  }

  .header-menu-wrapper .header-menu {
    flex-direction: column;
    text-align: initial;
  }

  .header-menu-wrapper .header-menu .header-lang {
    margin-bottom: 155px;
  }

  .header-menu-wrapper .header-menu ul li {
    margin-top: 15px;
    width: 100%;
    display: block;
    margin-left: -20px;
    background-color: #333;
    padding: 0px;
    border-top: 1px solid black;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.6);
  }

  .header-menu-wrapper .header-menu .submenu a {
    font-size: 11px;
    display: block;
    height: 32px;
    padding: 10px 20px;
    padding-left: 40px;
    border-bottom: 1px solid black;
  }
    
    /* Основная информация хедера */

  .header-content {
    width: 100%;
    flex-direction: column;
  }

  .header-content .header-txt {
    width: 100%;
    margin: 0px;
  }

  .header-content-title {
    width: 240px;
    line-height: 32px;
    margin: auto;
    text-align: center;
    margin-top: 30px;
    font-size: 25px;
  }

  .header-btn {
    margin: 0px auto;
  }
  .header .header-btn {
    background-color: inherit;
    margin-bottom: 40px;
  }

  .header-content-text {
    margin: 20px auto 40px;
    width: 100%;
    line-height: 20px;
    font-size: 14px;
    opacity: 0.7;
  }

  /* Достижения компании */

  .header-achievement {
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding: 0;
  }

  .header .header-achievement .header-achievement-item {
    text-align: start;
    margin: 30px 30px 30px 40px;
    width: 130px;
  }

  .header .header-achievement .header-achievement-item span {
    font-family: "Montserrat";
    font-size: 22px;
    font-weight: 700;
  }

  .header .header-achievement .header-achievement-item p {
    opacity: 0.7;
    font-family: "Montserrat";
    font-size: 10px;
    font-weight: 500;
    line-height: 15px;
    margin-top: 8px;
  }

  .header .header-achievement .header-achievement-item img {
    position: absolute;
    top: -10px;
  }
}
</style>