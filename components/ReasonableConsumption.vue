<template>
  <section class="reasonable-consumption">
    <div class="container">
      <header class="reasonable-consumption__header">
        <img
          class="insis-logo img-fluid"
          src="@/static/images/insis-logo.svg"
          alt="insis logo" />
        <a href="tel:88002506060" class="reasonable-consumption__phone"
          >8 800 250 60 60</a
        >
      </header>
      <div class="wrapper">
        <div>
          <h1 class="reasonable-consumption__title">
            За <span class="accent-text accent-text-title">разумное</span>
            <br />
            потребление
          </h1>
          <div class="description-wrapper">
            <div class="description">
              <div>
                до
                <span class="accent-text accent-text-description"
                  >100 Мбит/с
                </span>
              </div>

              <div>
                + от
                <span class="accent-text accent-text-description"
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
.reasonable-consumption {
  /* height: 812px; */
  background-color: var(--section-background-var-1);
}

.insis-logo {
  width: 293px;
  height: 74px;
  margin-right: 10px;
}

.reasonable-consumption__header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 100px;
}

.reasonable-consumption__phone {
  font-weight: 700;
  font-size: 36px;
  color: var(--section-background-var-2);
  z-index: 2;
}

.earth-image {
  /* position: absolute; */
  margin-top: -130px;
  top: 74px;
  left: 50%;
}

.main-content-wrapper {
  display: flex;
  justify-content: space-between;
}

.wrapper {
  display: flex;
  justify-content: space-between;
}

.container {
  position: relative;
}

.reasonable-consumption__title {
  font-weight: 700;
  color: var(--section-background-var-2);
  margin-bottom: 38px;
}

.accent-text-description {
  font-weight: 700;
  color: #4d423c;
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

.ladder-divider {
  background-color: red;
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

  .reasonable-consumption__title {
    font-size: 55px;
  }
}

@media screen and (max-width: 750px) {
  .reasonable-consumption {
    /* height: 666px; */
  }

  .earth-image {
    width: 690px;
    height: 585px;
  }

  .insis-logo {
    width: 193px;
    height: 49px;
  }

  .reasonable-consumption__phone {
    font-size: 24px;
  }

  .reasonable-consumption__title {
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
