<template>
  <section class="reasonable-consumption">
    <div class="container">
      <header class="header">
        <img
          class="header__insis-logo"
          src="@/static/images/insis-logo.svg"
          alt="insis logo" />

        <a href="tel:88002506060" class="header__phone">8 800 250 60 60</a>
      </header>

      <div class="main-content">
        <div>
          <h1 class="title">
            За <span class="accent-text title__accent-text">разумное</span>
            <br />
            потребление
          </h1>

          <div class="description-wrapper">
            <div class="description">
              <div>
                до
                <span class="accent-text description__accent-text"
                  >100 Мбит/с
                </span>
              </div>

              <div>
                + от
                <span class="accent-text description__accent-text"
                  >150 каналов</span
                >
              </div>
            </div>

            Первый месяц бесплатно
          </div>

          <button type="button" class="btn btn-primary main-button">
            Оставить заявку
          </button>
        </div>

        <img
          class="earth-image"
          src="@/static/images/earth.svg"
          alt="earth-image" />
      </div>
    </div>
  </section>
</template>

<style scoped>
.main-button {
  width: 275px;
}

.reasonable-consumption {
  background-color: var(--section-background-var-1);
}

.header__insis-logo {
  width: 293px;
  height: 74px;
  margin-right: 10px;
}

.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 100px;
}

.header__phone {
  font-weight: 700;
  font-size: 36px;
  color: var(--section-background-var-2);
  z-index: 2;
}

.earth-image {
  margin-top: -130px;
  top: 74px;
  left: 50%;
}

.main-content-main-content {
  display: flex;
  justify-content: space-between;
}

.main-content {
  display: flex;
  justify-content: space-between;
}

.container {
  position: relative;
}

.title {
  font-weight: 700;
  color: var(--section-background-var-2);
  margin-bottom: 38px;
}

.description__accent-text {
  font-weight: 700;
  color: var(--font-var-1);
}

.description-wrapper {
  position: relative;
  max-width: 470px;
  padding-left: 66px;
  margin-bottom: 38px;
  color: var(--font-var-1);
}

.description-wrapper::before {
  position: absolute;
  content: "";
  background-image: url("@/static/images/dash.svg");
  width: 38px;
  height: 8px;
  left: 0;
  top: 15px;
}

.description {
  display: flex;
}

@media screen and (max-width: 950px) {
  .description {
    display: block;
  }

  .description-wrapper {
    max-width: 275px;
  }

  .title {
    font-size: 55px;
  }
}

@media screen and (max-width: 750px) {
  .earth-image {
    width: 690px;
    height: 585px;
  }

  .header__insis-logo {
    width: 193px;
    height: 49px;
  }

  .header__phone {
    font-size: 24px;
  }

  .title {
    font-size: 40px;
  }

  .description-wrapper {
    max-width: 275px;
    font-size: 20px;
  }

  .main-button {
    width: 267px;
  }
}
</style>
