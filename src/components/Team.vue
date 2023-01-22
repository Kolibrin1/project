<template>
            <!-- СПИСОК КОМАНДЫ -->
            <div class="team o-container">
        <div class="team-title">
            <span>
                Команда
            </span>
        </div>
        <div class="team-list min-container">
            <div class="team-list-item">
                <div class="team-photo">
                    <img src="../assets/img/team/Sinica-S.jpg" alt="сотрудник">
                </div>
                <div class="team-employee">
                    <div class="team-employee-name">Сергей Синица</div>
                    <div class="team-employee-position">Руководитель отдела веб-разработки, канд. техн. наук, заместитель
                        директора</div>
                </div>
            </div>
            <div class="team-list-item">
                <div class="team-photo">
                    <img src="../assets/img/team/Agabekov-R.jpg" alt="сотрудник">
                </div>
                <div class="team-employee">
                    <div class="team-employee-name">Роман Агабеков</div>
                    <div class="team-employee-position">Руководитель отдела DevOPS, директор</div>
                </div>
            </div>
            <div class="team-list-item">
                <div class="team-photo">
                    <img src="../assets/img/team/Sinica-A.jpg" alt="сотрудник">
                </div>
                <div class="team-employee">
                    <div class="team-employee-name">Алексей Синица</div>
                    <div class="team-employee-position">Руководитель отдела поддержки сайтов</div>
                </div>
            </div>
            <div class="team-list-item">
                <div class="team-photo">
                    <img src="../assets/img/team/Bochkaryova-D.jpg" alt="сотрудник">
                </div>
                <div class="team-employee">
                    <div class="team-employee-name">Дарья Бочкарёва</div>
                    <div class="team-employee-position">Руководитель отдела продвижения, контекстной рекламы и
                        контент-поддержки
                        сайтов</div>
                </div>
            </div>
            <div class="team-list-item">
                <div class="team-photo">
                    <img src="../assets/img/team/Torkunova-I.jpg" alt="сотрудник">
                </div>
                <div class="team-employee">
                    <div class="team-employee-name">Ирина Торкунова</div>
                    <div class="team-employee-position">Менеджер по работе с клиентами</div>
                </div>
            </div>
            <div class="team-list-item">
                <div class="team-photo">
                    <img src="../assets/img/team/Dyakova-E.png" alt="сотрудник">
                </div>
                <div class="team-employee">
                    <div class="team-employee-name">Эльмира Дьякова</div>
                    <div class="team-employee-position">Руководитель отдела по работе с клиентами</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default
    {
        name: 'Team'
    }
</script>
<style scoped>
    /* КОМАНДА */

.team {
    width: 100%;
    margin-top: 160px;
}

.team-title {
    font-weight: bold;
    font-size: 42px;
    line-height: 51px;
    text-align: center;
    color: #050C33;
}

.team-list {
    width: 1080px;
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin: 0 auto;
}

.team-list-item {
    width: 280px;
    margin-top: 80px;
}

.team-photo {
    margin-bottom: 30px;
}

.team-photo img {
    width: 280px;
    height: 280px;
}

.team-txt-name {
    color: #050C33;
    font-weight: bold;
    font-size: 16px;
    margin-bottom: 10px;
}

.team-txt-position {
    font-size: 16px;
    line-height: 22px;
    color: #050C33;
    opacity: 0.7;
}
@media screen and (max-width: 575px) {
      /* КОМАНДА */
    .o-container {
      width: 100%;
    }
  
    .min-container {
      width: 100%;
    }
    
  .team {
    padding: 0px 15px;
  }

  .team-title {
    margin-bottom: 60px;
    font-size: 25px;
  }

  .team-list .team-list-item {
    margin-bottom: 20px;
    margin-top: 0px;
    width: 155px;
  }

  .team-photo {
    margin-bottom: 20px;
  }

  .team-photo img {
    width: 155px;
    height: 155px;
  }

  .team-employee .team-employee-name {
    font-size: 14px;
  }

  .team-employee .team-employee-position {
    font-family: "Montserrat";
    font-weight: 500;
    font-size: 12px;
    line-height: 22px;
    color: #050C33;
    opacity: 0.7;
  }

}
</style>