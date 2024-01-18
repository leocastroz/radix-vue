<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderSide from './components/HeaderSide.vue'
</script>

<template>
  <header>
    <div>
      <HeaderSide  />
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/sobre">sobre</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

