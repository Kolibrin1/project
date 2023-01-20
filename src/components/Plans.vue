<template>
        <!-- ТАРИФЫ И ИХ ПРЕИМУЩЕСТВА -->
        <div class="plans">
        <div class="plans-body o-container">
            <div class="plans-title" id="plans">
                <span>
                    Тарифы
                </span>
            </div>
            <div class="plans-cards">
                <div class="plans-card-starter plans-card">
                    <div class="plans-wrapper">
                        <div class="plans-card-title">
                            <h4>
                                Стартовый
                            </h4>
                            <div class="plans-card-price">
                                <h3>
                                    2000 <span>₽</span>
                                </h3>
                                <p>в час</p>
                            </div>
                        </div>

                        <div class="plans-card-line"></div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Предоплата от 2 часов</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Консультации и работы по SEO</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Услуги дизайнера</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Стандартное время реакции</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Неиспользованные оплаченные часы переносятся на следующий месяц</p>
                        </div>
                        <input class="plans-btn" type="button" value="ОСТАВИТЬ ЗАЯВКУ!">
                    </div>
                </div>
                <div class="plans-card-business plans-card">
                    <div class="plans-wrapper">
                        <div class="plans-card-title">
                            <h4>
                                Бизнес
                            </h4>
                            <div class="plans-card-price">
                                <h3>
                                    2000 <span>₽</span>
                                </h3>
                                <p>в час</p>
                            </div>
                        </div>

                        <div class="plans-card-line"></div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Предоплата от 10 часов</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Консультации и работы по SEO</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Услуги дизайнера</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Высокое время реакции –
                                до 2 рабочих дней</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Неиспользованные часы не переносятся</p>
                        </div>
                        <input class="plans-btn" type="button" value="ОСТАВИТЬ ЗАЯВКУ!">
                    </div>
                </div>
                <div class="plans-card-vip plans-card">
                    <div class="plans-wrapper">
                        <div class="plans-card-title">
                            <h4>
                                VIP
                            </h4>
                            <div class="plans-card-price">
                                <h3>
                                    1800 <span>₽</span>
                                </h3>
                                <p>в час</p>
                            </div>
                        </div>

                        <div class="plans-card-line"></div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Предоплата от 100 часов</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Консультации и работы по SEO</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Услуги дизайнера</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Максимальное время
                                реакции – в день обращения</p>
                        </div>
                        <div class="plans-card-list-options">
                            <div class="plans-card-checkmark">
                                <img src="../assets/img/plans/Vector.svg" alt="">
                            </div>
                            <p>Неиспользованные часы не переносятся</p>
                        </div>
                        <input class="plans-btn" type="button" value="ОСТАВИТЬ ЗАЯВКУ!">
                    </div>
                </div>
            </div>
            <span class="plans-footer-text">Вам не подходят наши тарифы? Оставьте заявку и мы предложим вам
                индивидуальные
                условия!</span>
            <a href="#">ПОЛУЧИТЬ ИНДИВИДУАЛЬНЫЙ ТАРИФ</a>
        </div>
        <div class="big-D-background">
            <img src="../assets/img/plans/D-background.svg" alt="">
        </div>
    </div>
</template>
<script>
    export default
    {
        name: 'Plans'
    }
    $(document).ready(function(){

//УВЕЛИЧЕНИЕ ТАРИФОВ ПРИ НАВЕДЕНИИ

$('.plans-card-starter').mouseover(function(){
    $(this).addClass('scaled');
    $('.plans-card-business').addClass('business-scale');
});
$('.plans-card-starter').mouseout(function(){
    $(this).removeClass('scaled');
    $('.plans-card-business').removeClass('business-scale');
});
$('.plans-card-vip').mouseover(function(){
    $(this).addClass('scaled');
    $('.plans-card-business').addClass('business-scale');
});
$('.plans-card-vip').mouseout(function(){
    $(this).removeClass('scaled');
    $('.plans-card-business').removeClass('business-scale');
});
    });
</script>
<style scoped>
    /* ТАРИФЫ */

.plans {
    position: relative;
    height: 913px;
}

.plans-body {
    padding: 150px 0px;
}

.plans-body p {
    text-align: start;
    width: 468px;
    font-size: 16px;
    line-height: 22px;
    color: #050C33;
}

.plans-body a {
    display: block;
    width: 260px;
    color: #050C33;
    font-size: 12px;
    text-decoration: underline;
    margin: 24px auto;
}

.big-D-background {
    position: absolute;
    top: 0;
    right: 0;
}

.plans-card-line {
    width: 300px;
    height: 1px;
    opacity: 0.2;
    margin-top: 20px;
    margin-bottom: 50px;
    background-color: black;
}

/* заголовок*/

.plans-title {
    font-size: 42px;
    margin-bottom: 60px;
    position: relative;
    z-index: 4;
    font-weight: bold;
    line-height: 51px;
    align-items: center;
    text-align: center;
}

/* карточки */

.plans-cards {
    display: flex;
    justify-content: center;
    position: relative;
    align-items: center;
    margin-bottom: 52px;
}

.plans-card-title h4 {
    color: #F14D34;
    font-size: 22px;
    font-weight: 700;
}
.plans-card-price h3 {
    font-weight: bold;
    font-size: 72px;
    line-height: 72px;
    display: flex;
    align-items: center;
    text-transform: uppercase;
    color: #050C33;
}

.plans-card-price span {
    position: relative;
    font-weight: 500;
    font-size: 28px;
    line-height: 28px;
    top: -11px;
    color: #050C33;
}

.plans-card-price p {
    position: relative;
    right: 15px;
    font-size: 16px;
    line-height: 20px;
    display: flex;
    align-items: start;
    color: #050C33;
    opacity: 1;
}

/* анимация наведения на карточки */

.plans .scaled {
    z-index: 2;
    transform: scale(1.08);
    box-shadow: 0px 4px 60px rgba(162, 162, 162, 0.25);
}

.plans .scaled .plans-btn {
    color: white;
    background-color: #F14D34;
}

.plans .business-scale {
    padding-top: 85px;
    z-index: 1;
    transform: scale(0.93);
    box-shadow: none;
}

.plans .business-scale .plans-btn {

    width: 300px;
    margin-top: 50px;
    background-color: white;
    color: #F14D34;
}

/* тело карточек */

.plans-card {
    padding: 70px 20px 60px;
}

.plans-card p {
    color: #050C33;
    font-size: 16px;
    font-weight: 500;
    line-height: 20px;
    margin-left: 15px;
    opacity: 0.7;
}

.plans-wrapper {
    width: 330px;
    margin: 0px auto;
    margin-left: 20px;

}

/* кнопки*/

.plans-btn {
    color: #F14D34;
    font-size: 12px;
    width: 300px;
    height: 60px;
    border: 1px solid #F14D34;
    border-radius: 5px;
    display: flex;
    justify-content: center;
    margin-top: 20px;
    background-color: white;
    transition: 0.4s;
    cursor: pointer;
}

/* стартовый */

.plans-card-starter {
    position: relative;
    left: 20px;
    z-index: 1;
    width: 360px;
    height: 619px;
    border-radius: 5px;
    border: 1px solid rgba(0, 0, 0, 0.1);
    margin-right: 15px;
    background: white;
    transition: 0.4s;
}

.plans-card-starter .plans-card-line {
    width: 270px;
}

.plans-card-starter .plans-wrapper {
    width: 300px;
    margin: 0px auto;
}

/* бизнес */

.plans-card-business {
    box-shadow: 0px 4px 60px rgba(162, 162, 162, 0.25);
    z-index: 2;
    width: 390px;
    height: 665px;
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    background: white;
    transition: 0.4s;
}

.plans-card-business .plans-card-line {
    margin-bottom: 65px;
}

.plans-card-business .plans-btn {
    background-color: #F14D34;
    color: white;
}


/* vip */

.plans-card-vip {
    position: relative;
    right: 20px;
    z-index: 1;
    width: 360px;
    height: 619px;
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    margin-left: 15px;
    background: white;
    transition: 0.4s;
}

.plans-card-vip .plans-card-line {
    width: 270px;
}

.plans-card-vip .plans-wrapper {
    width: 300px;
    margin: 0px auto;
}

/* возможности тарифов */

.plans-card-list-options {
    margin-bottom: 0px;
    display: flex;
    width: 300px;
}

.plans-card-checkmark {
    width: 30px;
    height: auto;
}

/* футер */

.plans-footer-text {
    display: block;
    margin: 53px auto 0 auto;
    text-align: center;
    font-weight: 500;
    font-size: 16px;
    line-height: 22px;
    width: 468px;
    opacity: 0.5;
}
@media screen and (max-width: 575px) {
    .plans {
    height: 1000px;
    margin: 0;
  }

  .plans-card-price h3 {
    font-size: 40px;
  }

  .plans .scaled {
    transform: scale(1);
    box-shadow: none;
  }

  .plans .business-scale .plans-btn {
    width: 100%;
    height: 60px;
    margin-top: 0;
    background-color: white;
    color: #F14D34;
  }

 .plans .business-scale {
    transform: scale(1);
    box-shadow: none;
  }

  .plans-card-business {
    z-index: 1;
  }

  .plans-card-business .plans-wrapper {
    width: 300px;
    margin: 0px auto;
    margin-left: 0;
  }
  
  .plans .scaled .plans-btn {
    width: 100%;
    background-color: #F14D34;
  }

  .plans-body .plans-title {
    font-size: 25px;
    margin-bottom: 20px;
  }

  .plans-body>p {
    width: 100%;
    font-size: 16px;
    line-height: 22px;
  }

  .plans-cards {
    margin: 0 20px;
    flex-direction: column;
  }

  .plans-cards .plans-card {
    padding: 30px 10px 20px;
    margin: 10px 0px;
    width: 100%;
    height: auto;
  }

  .plans-footer-text {
    text-align: center;
    width: 100%;
    margin: 20px auto;
  }

  .plans-card-starter {
    left: 0px;
  }

  .plans-card-vip {
    right: 0px;
  }
  
  .plans-btn {
    margin: 0px auto;
    background-color: inherit;
    color: #f14d34;
    width: 100%;
  }

  .plans-card-line {
    width: 100%;
  }

  .plans-card .plans-wrapper {
    width: 100%;
  }

  .plans-card p {
    font-size: 14px;
  }
}

</style>