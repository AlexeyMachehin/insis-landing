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
  name: 'IndexPage',
};
</script>

<style scoped>
.main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: blue;
}
</style>
