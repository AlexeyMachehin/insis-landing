<template>
  <section class="do-not-overpay">
    <div class="ladder-divider divider-rotate"></div>

    <div class="container">
      <div class="main-content">
        <img
          class="wallet-image"
          src="@/static/images/wallet.svg"
          alt="wallet" />

        <div class="description">
          <h2 class="description__title">
            <span class="accent-text accent-text-title"
              >Не переплачивайте!</span
            >
            За то, что другие навязывают.
          </h2>

          <div class="description__content">
            <span class="description__content__accent-text"
              >Рациональное потребление</span
            >
            – пользоваться тем, что действительно надо
          </div>
        </div>
      </div>

      <ul class="advantages-list">
        <li class="advantage">
          <img
            class="advantage__image"
            src="@/static/images/only-required-speed.svg"
            alt="only-required-speed" />

          <div class="advantage__description">
            Только
            <span class="advantage__description__accent-text">необходимая </span
            >скорость
          </div>
        </li>

        <li class="advantage">
          <img
            class="advantage__image"
            src="@/static/images/only-reasonable-price.svg"
            alt="only-reasonable-price" />

          <div class="advantage__description">
            Только
            <span class="advantage__description__accent-text">разумная</span>
            цена
          </div>
        </li>

        <li class="advantage">
          <img
            class="advantage__image"
            src="@/static/images/only-favorable-conditions.svg"
            alt="only-favorable-conditions" />

          <div class="advantage__description">
            Только
            <span class="advantage__description__accent-text">выгодные</span>
            условия
          </div>
        </li>
      </ul>
    </div>
    <div class="ladder-divider"></div>
  </section>
</template>

<style scoped>
.advantage__image {
  width: 86px;
  height: 86px;
}

.advantage__description__accent-text {
  font-weight: 600;
  color: var(--reasonable-consumption-accent-text);
}

.description__content__accent-text {
  font-weight: 700;
}

.advantage__description {
  width: 184px;
  margin-left: 35px;
  font-family: "Montserrat Alternates", sans-serif;
  font-size: 22px;
  line-height: 27px;
}

.advantages-list {
  display: flex;
  justify-content: space-between;
  margin-top: 115px;
  margin-bottom: 160px;
  color: var(--font-var-2);
}

.advantage {
  display: flex;
  margin-right: 50px;
}

.do-not-overpay {
  background-color: var(--section-background-var-2);
}

.main-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.description {
  margin-left: 20px;
  max-width: 610px;
  color: var(--font-var-2);
}

.description__title {
  margin-bottom: 40px;
}

@media screen and (max-width: 1180px) {
  .advantage {
    flex-direction: column;
    align-items: flex-start;
  }

  .advantage__description {
    margin-left: 0;
    margin-top: 25px;
  }
}

@media screen and (max-width: 1120px) {
  .wallet-image {
    width: 330px;
    height: 350px;
  }
}

@media screen and (max-width: 920px) {
  .wallet-image {
    width: 280px;
    height: 300px;
  }

  .description__title {
    font-size: 32px;
  }

  .description__content {
    font-size: 20px;
  }

  .description__content__accent-text {
    font-size: 20px;
  }
}

@media screen and (max-width: 700px) {
  .wallet-image {
    width: 123px;
    height: 130px;
  }

  .advantage__description {
    font-size: 16px;
    width: 100px;
  }

  .advantage__description__accent-text {
    font-size: 16px;
  }

  .main-content {
    align-items: flex-start;
  }
}
</style>
