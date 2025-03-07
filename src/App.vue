<template>
  <ButtonCounter></ButtonCounter> <!--PascalCase-->
  <button-counter></button-counter> <!--Kebab-case-->
  <hr>
  <div style="background-color: orange; padding: 5px">
    This is the root component.
    <ComponentA></ComponentA>
    <ComponentA></ComponentA>
  </div>
</template>

<script setup>
import ButtonCounter from "./ButtonCounter.vue";
import ComponentA from "./ComponentA.vue";
</script>

<style scoped></style>
