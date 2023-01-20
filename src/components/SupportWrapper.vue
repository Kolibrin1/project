<template>
    <div class="support-wrapper o-container">
        <div class="support-wrapper-body">
            <div class="support-expertise">
                <div class="support-expertise-title">
                    <span>Экспертиза в Drupal, опыт 14 лет</span>
                </div>
                <div class="support-expertise-list">
                    <div class="support-expertise-item">
                        <p>
                            Только системный подход – контроль версий, резервирование
                            и тестирование!
                        </p>
                    </div>
                    <div class="support-expertise-item">
                        <p>
                            Только Drupal сайты,
                            не берем на поддержку сайты на других CMS!
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="support-druplicon">
            <img src="../assets/img/support/druplicon.svg" alt="">
        </div>
        <div class="support-notebook">
            <img src="../assets/img/support/notebook.svg" alt="">
        </div>
    </div>
</template>
<script>
    export default
    {
        name: 'SupportWrapper'
    }
</script>
<style scoped>
/* druplicon на фоне */

.support-druplicon {
    z-index: 1;
    position: absolute;
    top: 0;
    right: 0;
    width: 1060px;
    height: 839px;
}

/* Ноутбук на фоне */

.support-notebook {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 760px;
    height: 562px;
    z-index: 3;
}

/* support-wrapper && title */

.support-wrapper {
    position: relative;
    height: 839px;
    background: linear-gradient(261.2deg, rgba(255, 255, 255, 0.276) -114.85%, rgba(255, 255, 255, 0) 69.04%), #040613;
    box-shadow: 0px 5px 5px rgba(0, 0, 0, 0.3);
}

.support-wrapper .support-wrapper-body {
    padding-top: 205px;
    position: relative;
    z-index: 2;
}

.support-expertise {
    margin-top: 197px;
    margin-left: auto;
    margin-right: 430px;
    width: 580px;
}

.support-expertise-title {
    color: white;
    width: 580px;
    font-size: 42px;
    line-height: 51px;
    font-weight: 700;
}

/* Список элементов support*/

.support-expertise-list {
    display: flex;
}

.support-expertise-item {
    width: 256px;
    height: 100px;
    padding: 10px 0px 0px 13px;
    border-left: 3px solid #F14D34;
    margin-right: 20px;
    margin-top: 60px;
}

.support-expertise-item p {
    color: white;
    opacity: 0.7;
    font-size: 16px;
    line-height: 22px;
}

@media screen and (max-width: 575px) {
    .support-wrapper {
    padding: 0px 10px;
    height: 1000px;
  }

  .support-expertise-title {
    font-size: 25px;
    width: 300px;
    margin-top: -100px;
    line-height: 30px;
  }

  .support-expertise-list {
    flex-direction: column;
  }

  .support-expertise-list .support-expertise-item {
    margin-top: 30px;
  }

  .support-notebook {
    top: 685px;
    width: 390px;
    height: 450px;
  }

  .support-notebook img {
    width: 400px;
  }
}
</style>