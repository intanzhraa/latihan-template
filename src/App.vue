<template>
  <div>
    <NavbarComponent></NavbarComponent>
    <CarouselComponent></CarouselComponent>
    <br>
    <CardComponent></CardComponent>
    <Footer></Footer>
  </div>
</template>

<script setup>
import NavbarComponent from './components/NavbarComponent.vue';
import CarouselComponent from './components/CarouselComponent.vue';
import CardComponent from './components/CardComponent.vue';
import { Footer } from 'flowbite-vue';
</script>