<template>
    <!-- ПОДДЕРЖКА -->
   <div class="support o-container" id="support">
    <div class="support-title">
        <span>
            Поддержка от Drupal-coder
        </span>
    </div>
    <div class="support-list">
        <div class="support-item support-item-1">
            <p class="support-item-number">01.</p>
            <p class="support-item-title">
                Постановка задачи по Email
            </p>
            <p class="support-item-txt">
                Удобная и привычная модель постановки задач, при которой задачи фиксируются и никогда не
                теряются.
            </p>
        </div>
        <div class="support-item support-item-2">
            <p class="support-item-numberr">02.</p>
            <p class="support-item-title">
                Система Helpdesk – отчетность, прозрачность
            </p>
            <p class="support-item-txt">
                Возможность посмотреть все заявки в работе
                отработанные часы
                личном кабинете через браузер.
            </p>
        </div>
        <div class="support-item support-item-3">
            <p class="support-item-number">03.</p>
            <p class="support-item-title">
                Расширенная техническая поддержка
            </p>
            <p class="support-item-txt">
                Возможность организации расширенной техподдержки с 6:00
                до 22:00 без выходных.
            </p>
        </div>
        <div class="support-item support-item-4">
            <p class="support-item-number">04.</p>
            <p class="support-item-title">
                Персональный менеджер проекта
            </p>
            <p class="support-item-txt">
                Ваш менеджер проекта всегда в курсе текущего состояния проекта
                и в любой момент готов ответить на любые вопросы.
            </p>
        </div>
        <div class="support-item support-item-5">
            <p class="support-item-number">05.</p>
            <p class="support-item-title">
                Удобные способы оплаты
            </p>
            <p class="support-item-txt">
                Безналичный расчет по договору или электронные деньги: WebMoney, Яндекс.Деньги, Paypal.
            </p>
        </div>
        <div class="support-item support-item-6">
            <p class="support-item-number">06.</p>
            <p class="support-item-title">
                Работаем с SLA и NDA
            </p>
            <p class="support-item-txt">
                Работа в рамках соглашений
                о конфиденциальности
                и об уровне качетсва работ.
            </p>
        </div>
        <div class="support-item support-item-7">
            <p class="support-item-number">07.</p>
            <p class="support-item-title">
                Штатные специалисты
            </p>
            <p class="support-item-txt">
                Надежные штатные специалисты, никаких фрилансеров.
            </p>
        </div>
        <div class="support-item support-item-8">
            <p class="support-item-number">08.</p>
            <p class="support-item-title">
                Удобные каналы связи
            </p>
            <p class="support-item-txt">
                Консультации по телефону, скайпу,
                в месенджерах.
            </p>
        </div>
    </div>
</div>
</template>
<script>
    export default
    {
        name: 'Support'
    }
</script>
<style scoped>
    /* --- ПОДДЕРЖКА ОТ ПРОЕКТА DRUPAL --- */

.support {
    margin-top: 160px;
    color: #050C33;
}

/* Общая информация */

.support-title {
    text-align: center;
    font-size: 42px;
    font-weight: 700;
    line-height: 51px;
    width: 406px;
    margin: 0px auto -140px;
}

/* Основные услуги */

.support-list {
    width: 1184px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 5px;
    justify-content: center;
    align-items: center;
    margin-left: 300px;
}

.support-item {
    z-index: 2;
    position: relative;
    overflow: hidden;
    width: 292px;
    height: 292px;
    padding: 30px 20px 0px 28px;
    border-radius: 5px;
    box-shadow: 0px 5px 5px rgba(0, 0, 0, 0.1);
    background-color: white;
    top: 205px;
}

/* Информация с карточек услуг */

.support-item .support-item-number {
    font-size: 12px;
    opacity: 0.5;
    font-weight: 700;
    margin-bottom: 10px;
}

.support-item .support-item-title {
    font-weight: 700;
    font-size: 18px;
    line-height: 22px;
    margin-bottom: 12px;
}

.support-item .support-item-txt {
    font-weight: 500;
    font-size: 16px;
    line-height: 22px;
    opacity: 0.7;
}

/* Картинки списка услуг */

.support-item-1::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support1.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-2::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support2.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-3::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support3.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-4::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support4.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-5::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support5.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-6::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support6.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-7::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support7.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}

.support-item-8::before {
    content: "";
    width: 84px;
    height: 84px;
    background: url("../assets/img/support/support8.svg") no-repeat;
    position: absolute;
    right: 0;
    bottom: -2px;
}
@media screen and (max-width: 575px) {
.support {
    margin: 0;
    padding: 10px;
  }

  .support-list {
    margin: 0;
    width: 100%;
    display: grid;
    grid-template-columns: 1fr
  }

  .support-title {
    font-size: 30px;
    width: 250px;
    line-height: 35px;
  }

  .support-item {
    width: 100%;
  }
}
</style>