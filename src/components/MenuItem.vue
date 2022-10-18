<template>
  <a href="#" class="menu__item">
    <q-icon :name="menu.icon" class="menu__item--icon"></q-icon>
    <div class="menu__item--desc">{{ menu.nombre }}</div>
  </a>
</template>
<script setup>
const props = defineProps(['menu']);
</script>
