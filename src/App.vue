<template>
  <BaseButton></BaseButton>
  <BaseButton
    buttonText="elevated"
    variant="elevated"
    buttonSize="small"
    rounded="small"
  ></BaseButton>
  <BaseButton buttonText="text" variant="text"> </BaseButton>
  <BaseButton
    buttonText="flat"
    variant="flat"
    buttonSize="large"
    rounded="large"
  >
  </BaseButton>
  <BaseButton buttonText="outlined" variant="outlined" color="" bkcolor="white">
  </BaseButton>
  <br />
  <BaseButton>
    <template #prepend> prependIcon </template>
    <template #append> appendIcon </template>
  </BaseButton>
</template>

<script>
import BaseButton from "./components/Base-Button.vue";
export default {
  name: "App",
  components: {
    BaseButton,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
Button {
  margin: 20px;
}
</style>
