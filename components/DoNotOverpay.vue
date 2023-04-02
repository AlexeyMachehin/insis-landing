<template>
  <section class="do-not-overpay">
    <div class="ladder-divider divider-rotate"></div>
    <div class="container">
      <div class="main-content">
        <img src="@/static/images/wallet.svg" alt="wallet" />
        <div class="description">
          <h2 class="do-not-overpay__title">
            <span class="accent-text accent-text-title"
              >Не переплачивайте!</span
            >
            За то, что другие навязывают.
          </h2>
          <div>
            <span class="accent-term">Рациональное потребление</span>
            – пользоваться тем, что действительно надо
          </div>
        </div>
      </div>
      <div class="advantages-list">
        <div class="advantage">
          <img
            src="@/static/images/only-required-speed.svg"
            alt="only-required-speed" />
          <div class="advantage-description">Только необходимая скорость</div>
        </div>
        <div class="advantage">
          <img
            src="@/static/images/only-reasonable-price.svg"
            alt="only-reasonable-price" />
          <div class="advantage-description">Только разумная цена</div>
        </div>
        <div class="advantage">
          <img
            src="@/static/images/only-favorable-conditions.svg"
            alt="only-favorable-conditions" />
          <div class="advantage-description">Только выгодные условия</div>
        </div>
      </div>
    </div>
    <div class="ladder-divider"></div>
  </section>
</template>

<style scoped>
.accent-term {
  font-weight: 700;
}

.advantage-description {
  width: 184px;
  margin-left: 35px;
  margin-right: 120px;
  font-family: "Montserrat Alternates", sans-serif;
}

.advantages-list {
  display: flex;
  margin-top: 115px;
  margin-bottom: 160px;
  color: var(--font-var-2);
}

.advantage {
  display: flex;
}

.do-not-overpay {
  /* height: 850px; */
  background-color: var(--section-background-var-2);
}

.main-content {
  display: flex;
  align-items: center;
}

.description {
  max-width: 610px;
  margin-left: 166px;
  color: var(--font-var-2);
}

.do-not-overpay__title {
  /* font-weight: 700; */
  margin-bottom: 40px;
}
</style>
