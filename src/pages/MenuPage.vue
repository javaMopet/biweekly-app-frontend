<template>
  <div class="menu__container">
    <menu-item
      v-for="menu in menuOptions"
      :key="menu.id"
      :menu="menu"
    ></menu-item>
  </div>
</template>
<script setup>
import { ref } from 'vue';
import MenuItem from '../components/MenuItem.vue';

const menuOptions = ref([
  {
    id: 1,
    nombre: 'Tienda Universitaria',
    icon: 'book'
  },
  {
    id: 2,
    nombre: 'Libreria Universitaria',
    icon: 'lock'
  },
  {
    id: 3,
    nombre: 'Tienda de lety',
    icon: 'account_balance'
  }
]);
</script>

<style scoped lang="scss" src="../css/pages/menuPage.scss" />
