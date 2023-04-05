<template>
  <section class="internet-digital-tv">
    <div class="container">
      <h2 class="internet-digital-tv__title">
        Интернет + Цифровое
        <span class="accent-text internet-digital-tv__title__accent-text"
          >ТВ</span
        >
      </h2>

      <div>Чистая выгода</div>

      <div class="achievements-wrapper">
        <img
          class="computer-image img-fluid"
          src="@/static/images/computer.png"
          alt="computer" />

        <div class="achievement application">
          <img
            class="achievement__icon"
            src="@/static/images/monitor-icon.svg"
            alt="monitor-icon" />

          <div class="achievement__description">
            <span class="achievement__description__accent-text"
              >Приложение</span
            >
            Инсис ТВ
          </div>
        </div>

        <div class="achievement channels">
          <img
            class="achievement__icon"
            src="@/static/images/antenna.svg"
            alt="antenna-icon" />

          <div class="achievement__description">
            <span class="achievement__description__accent-text">Хороший</span>
            выбор каналов
          </div>
        </div>

        <div class="achievement support">
          <img
            class="achievement__icon"
            src="@/static/images/tech-support.svg"
            alt="tech-support-icon" />

          <div class="achievement__description">
            Надежная тех.поддержка в &#32;<span
              class="achievement__description__accent-text"
              >любое время</span
            >
          </div>
        </div>

        <div class="achievement connection">
          <img
            class="achievement__icon"
            src="@/static/images/lightning.svg"
            alt="lightning-icon" />

          <div class="achievement__description">
            <span class="achievement__description__accent-text">Быстрое</span>
            подключение
          </div>
        </div>

        <img
          class="application-arrow arrow"
          src="@/static/images/arrow.svg"
          alt="application-arrow" />

        <img
          class="channels-arrow arrow"
          src="@/static/images/arrow.svg"
          alt="channels-arrow" />

        <img
          class="support-arrow arrow"
          src="@/static/images/arrow.svg"
          alt="support-arrow" />

        <img
          class="connection-arrow arrow"
          src="@/static/images/arrow.svg"
          alt="connection-arrow" />
      </div>
    </div>
  </section>
</template>

<style scoped>
.application-arrow {
  position: absolute;
  left: 113px;
  top: 304px;
  transform: rotate(59.46deg);
}

.channels-arrow {
  position: absolute;
  right: 259px;
  top: 268px;
  transform: rotate(-176.73deg);
}

.support-arrow {
  position: absolute;
  right: 217px;
  top: 575px;
  transform: rotate(-128.76deg);
}

.connection-arrow {
  position: absolute;
  left: 263px;
  top: 624px;
}

.application {
  position: absolute;
  top: 241px;
}

.channels {
  position: absolute;
  right: 0;
  top: 215px;
}

.support {
  position: absolute;
  right: 32px;
  top: 711px;
}

.connection {
  position: absolute;
  left: 40px;
  top: 728px;
}

.achievement__description__accent-text {
  font-weight: 700;
}

.achievement__description {
  max-width: 200px;
  margin-left: 18px;
  color: var(--section-background-var-2);
}

.achievement {
  display: flex;
  align-items: center;
}

.achievements-wrapper {
  position: relative;
  margin-top: -135px;
}

.internet-digital-tv {
  background-color: var(--section-background-var-1);
}

.internet-digital-tv__title {
  font-weight: 400;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.internet-digital-tv__title__accent-text {
  font-weight: 400;
  color: var(--section-background-var-3);
}

@media screen and (max-width: 1140px) {
  .computer-image {
    margin-top: 30px;
  }
}

@media screen and (max-width: 1105px) {
  .application-arrow {
    left: 66px;
    transform: rotate(59.46deg) scale(0.7);
  }

  .channels-arrow {
    right: 172px;
    transform: rotate(-176.73deg) scale(0.7);
  }

  .support-arrow {
    right: 111px;
    top: 600px;
    transform: rotate(-128.76deg) scale(0.7);
  }

  .connection-arrow {
    left: 190px;
    transform: scale(0.7);
  }
}

@media screen and (max-width: 970px) {
  .computer-image {
    margin-top: 110px;
  }
}

@media screen and (max-width: 850px) {
  .computer-image {
    margin-top: 155px;
  }

  .connection-arrow {
    top: 591px;
    left: 56px;
    transform: matrix(0.51, -0.86, -0.86, -0.51, 0, 0) scale(0.7);
  }

  .channels-arrow {
    top: 225px;
    right: 243px;
    transform: rotate(148.3deg) scale(0.7);
  }

  .application-arrow {
    left: 21px;
  }
}

@media screen and (max-width: 800px) {
  .internet-digital-tv__title {
    font-size: 36px;
    letter-spacing: -0.02em;
  }
}

@media screen and (max-width: 790px) {
  .computer-image {
    margin-top: 190px;
  }
}

@media screen and (max-width: 750px) {
  .computer-image {
    margin-top: 220px;
  }

  .channels-arrow {
    top: 270px;
  }

  .channels {
    top: 242px;
  }
}

@media screen and (max-width: 710px) {
  .computer-image {
    margin-top: 240px;
  }

  .support-arrow {
    transform: rotate(-128.76deg) scale(0.5);
  }

  .application-arrow {
    top: 274px;
    left: 67px;
    transform: rotate(59.46deg) scale(0.5);
  }

  .connection-arrow {
    transform: matrix(0.51, -0.86, -0.86, -0.51, 0, 0) scale(0.5);
  }

  .channels-arrow {
    right: 153px;
    transform: rotate(148.3deg) scale(0.5);
  }

  .achievement__description {
    max-width: 130px;
    font-size: 16px;
    margin-left: 3px;
  }

  .achievement__description__accent-text {
    font-size: 16px;
  }

  .achievement__icon {
    transform: scale(0.7);
  }

  .achievements-wrapper {
    margin-top: -193px;
  }
}

@media screen and (max-width: 650px) {
  .achievements-wrapper {
    margin-top: -227px;
  }

  .connection-arrow {
    top: 530px;
    left: 74px;
  }

  .connection {
    left: 71px;
    top: 631px;
  }

  .support-arrow {
    right: 162px;
    top: 539px;
    transform: rotate(-99.18deg) scale(0.5);
  }

  .support {
    right: 53px;
    top: 636px;
  }

  .application-arrow {
    top: 296px;
  }

  .application {
    top: 278px;
    left: 52px;
  }

  .channels {
    top: 269px;
    right: 19px;
  }
}
</style>
