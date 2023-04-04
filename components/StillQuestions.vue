<template>
  <section class="questions">
    <div class="ladder-divider divider-rotate"></div>
    <div class="container">
      <div class="questions__main">
        <div class="still-questions">
          <h2 class="still-questions__title">Остались вопросы?</h2>
          <div>Оставляй заявку</div>
        </div>

        <div class="callback">
          <div class="callback__achievement">
            Объясняем понятно, решаем быстро
          </div>

          <form class="callback__form" action="">
            <input
              class="callback__input"
              type="tel"
              placeholder="+7 (___) ___-__-__" />
            <button class="btn btn-primary main-button">Перезвоните мне</button>
          </form>

          <div class="agreement">
            Нажимая на кнопку «Оставить заявку», вы даёте согласие на обработку
            персональных данных
          </div>
        </div>
      </div>

      <footer class="questions__footer">
        <div class="logo-wrapper">
          <img
            src="@/static/images/insis-footer-logo.svg"
            alt="insis-footer-logo" />
          <div class="logo-years">2007-2022 год</div>
        </div>

        <div class="social-wrapper">
          <div class="social-title">Мы в соц. сетях:</div>
          <div class="icons-wrapper">
            <a class="icon-link" href="#"
              ><img src="@/static/images/vk-logo.svg" alt="vk-logo"
            /></a>
            <a class="icon-link" href="#"
              ><img src="@/static/images/youtube-logo.svg" alt="youtube-logo"
            /></a>
          </div>
        </div>

        <div class="contacts-wrapper">
          <a href="tel:88002506060" class="questions__footer__phone"
            >8-800-250-60-60</a
          >
          <a href="mailto:info@profintel.ru" class="questions__footer__mail"
            >info@profintel.ru</a
          >
        </div>
      </footer>
    </div>
  </section>
</template>

<style scoped>
.main-button {
  position: absolute;
  width: 259px;
  right: 0;
}

.callback__form {
  position: relative;
  margin: 38px 0;
}

.callback__input {
  width: 100%;
  height: 77px;
  padding-left: 48px;
  border-radius: 39px;
}

.questions__footer__mail {
  font-weight: 600;
  font-size: 15px;
  color: var(--font-var-2);
  text-decoration-line: underline;
}

.questions__footer__phone {
  font-weight: 700;
  color: var(--font-var-2);
}

.contacts-wrapper {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.icon-link {
  display: flex;
}

.icons-wrapper {
  display: flex;
  justify-content: space-between;
}

.social-title {
  margin-bottom: 5px;
  font-size: 12px;
}

.logo-years {
  font-weight: 300;
  font-size: 12px;
  margin-top: 10px;
}

.questions__footer {
  display: flex;
  justify-content: space-between;
  padding-top: 66px;
  margin-top: 96px;
  border-top: var(--dashed-border);
}

.agreement {
  font-size: 14px;
}

.callback {
  max-width: 562px;
}

.questions__main {
  display: flex;
}

.still-questions__title {
  margin-bottom: 33px;
}

.still-questions {
  position: relative;
  max-width: 305px;
  margin-right: 170px;
}

.still-questions::after {
  position: absolute;
  content: "";
  width: 260px;
  height: 65px;
  background-image: url("@/static/images/still-questions-arrow.svg");
  background-repeat: no-repeat;
  top: 185px;
  left: 136px;
}

.questions {
  background-color: var(--section-background-var-3);
  color: var(--font-var-2);
}

@media screen and (max-width: 1105px) {
  .container {
    padding-left: 0;
    padding-right: 0;
  }

  .questions__main {
    flex-direction: column;
    align-items: center;
  }

  .still-questions::after {
    content: none;
  }

  .questions__footer {
    flex-direction: column;
    align-items: center;
    gap: 30px;
  }

  .logo-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    order: 1;
  }

  .contacts-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    order: 2;
  }

  .social-wrapper {
    order: 3;
  }

  .callback__achievement {
    display: none;
  }

  .still-questions {
    margin: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .still-questions__title {
    text-align: center;
  }

  .callback__form {
    position: static;
  }

  .callback {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 353px;
  }

  .main-button {
    position: static;
    width: 100%;
    margin-top: 23px;
  }
}
</style>
