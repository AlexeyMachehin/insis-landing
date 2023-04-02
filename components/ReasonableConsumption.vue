<template>
  <section class="reasonable-consumption">
    <div class="container">
      <header class="reasonable-consumption__header">
        <img
          class="insis-logo img-fluid"
          src="@/static/images/insis-logo.svg"
          alt="insis logo" />
        <a href="tel:88002506060" class="reasonable-consumption_phone"
          >8 800 250 60 60</a
        >
      </header>
      <h1 class="reasonable-consumption__title">
        За <span class="accent-text accent-text-title">разумное</span> <br />
        потребление
      </h1>
      <div class="description">
        до <span class="accent-text accent-text-description">100 Мбит/с</span> +
        от <span class="accent-text accent-text-description">150 каналов</span>
        Первый месяц бесплатно
      </div>
      <button type="button" class="btn btn-primary main-button">
        Оставить заявку
      </button>
      <img
        class="earth-image"
        src="@/static/images/earth.svg"
        alt="earth-image" />
    </div>
  </section>
</template>

<style scoped>
.reasonable-consumption {
  height: 812px;
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

.reasonable-consumption_phone {
  font-weight: 700;
  font-size: 36px;
  color: var(--section-background-var-2);
  z-index: 2;
}

.earth-image {
  position: absolute;
  width: 763px;
  height: 650px;
  top: 74px;
  left: 50%;
}

.main-content-wrapper {
  display: flex;
  justify-content: space-between;
}

.container {
  position: relative;
}

.reasonable-consumption__title {
  font-family: "Montserrat Alternates", sans-serif;
  font-weight: 700;
  font-size: 48px;
  color: var(--section-background-var-2);
  margin-bottom: 38px;
}

.accent-text-title {
  color: var(--reasonable-consumption-accent-text);
}

.accent-text-description {
  font-weight: 700;
  color: #4d423c;
}

.description {
  position: relative;
  max-width: 470px;
  padding-left: 66px;
  margin-bottom: 38px;
}

.description::before {
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

@media screen and (max-width: 825px) {
  .description {
    max-width: 400px;
  }
}

@media screen and (max-width: 716px) {
  .reasonable-consumption {
    height: 666px;
  }

  .earth-image {
    width: 690px;
    height: 585px;
  }

  .insis-logo {
    width: 193px;
    height: 49px;
  }

  .reasonable-consumption_phone {
    font-size: 24px;
  }

  .reasonable-consumption__title {
    font-size: 45px;
  }

  .description {
    max-width: 235px;
    font-size: 20px;
  }

  .main-button {
    width: 267px;
  }
}
</style>
