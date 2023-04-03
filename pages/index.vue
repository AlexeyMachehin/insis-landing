<template>
  <main class="main">
    <ReasonableConsumption />
    <DoNotOverpay />
    <InternetDigitalTv />
    <StillQuestions />
  </main>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style scoped>
.main {
  /* height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center; */
}

section {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>
