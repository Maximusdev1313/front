<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="">
    <header>
      <div class="wrapper">
        <nav>
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
        </nav>
      </div>
    </header>

    <RouterView />
  </div>
</template>

<style scoped></style>
