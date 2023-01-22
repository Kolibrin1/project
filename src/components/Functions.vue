<template>
           <!-- СПИСОК ФУНКЦИЙ СЕРВИСА -->
        <div class="functions o-container">
        <div class="functions-title">
            <span>
                13 лет совершенствуем компетенции в Drupal поддержке!
            </span>
        </div>
        <div class="functions-text">
            <p>
                Разрабатываем и оптимизируем модули, расширяем функциональность сайтов, обновляем дизайн
            </p>
        </div>
        <div class="functions-list">
            <div class="f-icon">
                <img src="../assets/img/functions/competency-1.svg" alt="">
                <p>Добавление информации на сайт, создание новых разделов</p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-2.svg" alt="">
                <p>
                    Разработка и оптимизация модулей сайта
                </p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-3.svg" alt="">
                <p>
                    Интеграция с CRM, 1С, платежными системами, любыми веб-сервисами
                </p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-4.svg" alt="">
                <p>
                    Любые доработки функционала и дизайна
                </p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-5.svg" alt="">
                <p>
                    Аудит и мониторинг безопасности Drupal сайтов
                </p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-6.svg" alt="">
                <p>
                    Миграция, импорт контента и апгрейд Drupal
                </p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-7.svg" alt="">
                <p>
                    Оптимизация и ускорение Drupal сайтов
                </p>
            </div>
            <div class="f-icon">
                <img src="../assets/img/functions/competency-8.svg" alt="">
                <p>
                    Веб-маркетинг, консультации и работы по SEO
                </p>
            </div>
        </div>
    </div>
</template>
<script>
    export default
    {
        name: 'Functions'
    }
</script>

<style scoped>
    /* --- ФУНКЦИИ СЕРВИСА --- */

.functions {
    margin-top: 160px;
    width: 1440px;
}

/* Описание */

.functions-title {
    margin: 0px 700px 18px 339px;
    width: 750px;
    font-size: 42px;
    font-style: normal;
    font-weight: bold;
    line-height: 51px;
    margin-bottom: 18px;
    color: #050C33;
}

.functions-text {
    width: 580px;
    margin-left: 339px;
    font-size: 16px;
    line-height: 22px;
    color: #050C33;
    opacity: 0.7;
}

/*  Список функций  */

.functions-list {
    margin-left: 330px;
    margin-top: 63px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
}

.f-icon {
    align-self: center;
    justify-self: center;
    height: 200px;
    position: relative;
    width: 182px;
    margin-right: 147px;
    margin-bottom: 50px;
}

.f-icon p {
    margin-top: 25px;
    width: 182px;
    font-size: 16px;
    line-height: 22px;
    opacity: 0.7;
}

.f-icon::before {
    left: -30.22%;
    right: 67.58%;
    top: 8.76%;
    bottom: 54.64%;
    content: "";
    height: 71px;
    width: 114px;
    background: url(../assets/img/functions/icon-bg.svg) no-repeat;
    position: absolute;
}
@media screen and (max-width:575px) {
    .functions {
    padding: 60px 15px;
  }
  .o-container {
      width: 100%;
    }

  .functions-list {
    margin: 0;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    justify-content: space-between;
  }

  .functions .functions-title {
    padding: 10px 10px;
    margin: 0;
    font-size: 25px;
    line-height: 35px;
    width: 100%;
  }

  .functions .functions-text {
    margin: 0;
    padding: 20px 10px;
    width: 100%;
  }

  .f-icon {
    width: 100%;
    margin-right: 0px;
  }

  .f-icon p {
    width: 135px;
    font-size: 13px;
    margin-top: 25px;
    margin-left: 20px;
  }

  .f-icon img {
    margin: 0px auto;
    display: block;
  }

  .f-icon::before {
    left: 0;
    top: 8.76%;
    bottom: 54.64%;
    content: "";
    height: 71px;
    width: 114px;
    background: url(../assets/img/functions/icon-bg.svg) no-repeat;
    position: absolute;
  }
 
    
}
</style>