<template>
  <header class="header">
    <div class="header__wrapper">
      <div class="header__title">
        <SilverBookIcon />
        <div>Телефонный справочник</div>
      </div>
      <UIButton @click="logout" color="silver">
        ВЫХОД 
      </UIButton>
    </div>
  </header>
</template>

<script setup>
import SilverBookIcon from '@/assets/icons/SilverBookIcon.vue'

const logout = () => navigateTo('/')
</script>

<style>
@import url('./style.module.scss');
</style>
