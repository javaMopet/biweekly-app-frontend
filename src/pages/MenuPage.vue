<template>
  <div class="menu__container">
    <div class="menu__item">
      <a href="#" class="menu__item--btn">Tienda</a>
    </div>
    <div class="menu__item">
      <a href="#" class="menu__item--btn">Libreria</a>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const mivar = ref(1);
</script>
<style src="../css/pages/menuPage.scss" />
