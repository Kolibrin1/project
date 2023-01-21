<template>
        <!-- КЕЙСЫ -->
        <div class="cases o-container" id="cases">
        <div class="cases-title">
            <span>Последние кейсы</span>
        </div>
        <div class="cases-items">
            <div class="cases-width-380 cases-small-case">
                <img src="../assets/img/cases/image1.png" alt="">
                <div class="cases-text">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                    <p class="date">22.04.2019</p>
                    <p>Эти слова совершенно справедливы, однако гипнотический рифф продолжает паузный пласт.</p>
                </div>
            </div>
            <div class="cases-width-780" style="grid-column: 2/4;">
                <img src="../assets/img/cases/image2.png" alt="">
                <div class="cases-text">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                </div>
            </div>
            <div class="cases-width-380">
                <img src="../assets/img/cases/image3.png" alt="">
                <div class="cases-text">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                    <p class="date">22.04.2019</p>
                </div>
            </div>
            <div class="cases-width-380">
                <img src="../assets/img/cases/image4.png" alt="">
                <div class="cases-text">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                    <p class="date">22.04.2019</p>
                </div>
            </div>
            <div class="cases-width-380 cases-small-case">
                <img src="../assets/img/cases/image5.png" alt="">
                <div class="cases-text">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                    <p class="date">22.04.2019</p>
                    <p>Эти слова совершенно справедливы, однако гипнотический рифф продолжает паузный пласт.</p>
                </div>
            </div>
            <div class="cases-width-780" style="grid-column: 1/3;">
                <img src="../assets/img/cases/image6.png" alt="">
                <div class="cases-text">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                </div>
            </div>
            <div class="cases-width-380">
                <img src="../assets/img/cases/image7.png" alt="">
                <div class="cases-txt">
                    <span>Настройка выгрузки YML для Яндекс.Маркета</span>
                    <p class="date">22.04.2019</p>
                </div>
            </div>
        </div>
        <button class="cases-more">ПОКАЗАТЬ ЕЩЁ</button>
    </div>
</template>
<script>
    export default
    {
        name: 'Cases'
    }
</script>
<style>
    /* ПОСЛЕДНИЕ КЕЙСЫ */

.cases {
    width: 100%;
    margin-top: 318px;
}

.cases-title {
    font-size: 42px;
    font-weight: 700;
    color: #050C33;
    text-align: center;
}

.cases-items {
    width: 1180px;
    margin: 0 auto;
    margin-top: 60px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    justify-content: center;
}

.cases-items img {
    position: absolute;
    border-radius: 5px;
    z-index: 1;
}

.cases-items span {
    color: white;
    font-size: 18px;
    line-height: 22px;
    font-weight: bold;
    width: 320px;
}

.cases-text {
    width: 380px;
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 4;
}

.cases-text .date {
    font-size: 12px;
    color: white;
    font-size: 12px;
    font-weight: bold;
    margin-top: 5px;
    opacity: 0.5;
}

.cases-text p {
    font-size: 14px;
    line-height: 22px;
    color: #050C33;
    margin-top: 20px;
    opacity: 0.7;
}

.cases-width-380 {
    position: relative;
    width: 380px;
    height: 475px;
    margin-bottom: 20px;
}

.cases-width-380 .cases-text {
    padding: 40px 50px;
}

.cases-width-780 {
    position: relative;
    width: 780px;
    height: 475px;
    margin-bottom: 20px;
    margin-right: 20px;
}

.cases-width-780 .cases-text {
    padding: 40px;
}

.cases-small-case .cases-text {
    padding: 70px 30px;
}

.cases-small-case .cases-text .date {
    color: #050C33;
}

.cases-small-case .cases-text span {
    color: #050C33;
}

.cases-more {
    font-size: 12px;
    color: #050C33;
    border-radius: 5px;
    background-color: white;
    width: 260px;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid rgba(5, 12, 51, 0.2);
    margin: 20px auto;
}
@media screen and (max-width: 575px) {
    .cases {
    margin-top: 1200px;
  }

  .cases-title {
    margin-bottom: 30px;
    font-size: 25px;
  }

  .cases-items {
    width: 100%;
    margin: 0;
    padding: 0 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .cases-width-380 {
    width: 100%;
    height: 440px;
    margin-bottom: 0px;
  }

  .cases-width-380 img {
    width: 100%;
  }

  .cases-text {
    width: 100%;
    margin: 0 auto;
  }

  .cases-width-380 .cases-text {
    margin: 20px;
    padding: 0;
  }

  .cases-small-case .cases-text {
    width: 100%;
    margin: 0 auto;
    padding: 0;
  }

  .cases-width-780 {
    width: 100%;
    height: 440px;
    margin-bottom: 0px;
    margin-right: 0px;
  }
  
  .cases-width-780 img {
    width: 100%;
    height: 320px;
  }

  .cases-width-780 span {
    position: absolute;
    top: -100px;
    right: 0;
    padding: 0;
    color: #fff;
  }
}
</style>