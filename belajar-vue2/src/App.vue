<template>
  <div>
    <NavbarComponent></NavbarComponent>
    <br>
    <Header></Header>
    <br>
    <h1 align="center">IKLAN</h1>
    <SidebarComponent></SidebarComponent>
    <br>
    <h1 class="m-2">Pilihan Anda</h1>
    <ContentPage></ContentPage>
    <br>
    <h1 class="m-2">Gallery</h1>
    <GalleryComponent></GalleryComponent>
    <br>
    <FooterComponent></FooterComponent>
    <br>
  </div>
</template>
<script setup> 
import NavbarComponent from './components/NavbarComponent.vue';
import Header from './components/HeaderComponent.vue';
import SidebarComponent from './components/SidebarComponent.vue';
import ContentPage from './components/ContentPage.vue';
import FooterComponent from './components/FooterComponent.vue';
import GalleryComponent from './components/GalleryComponent.vue'

</script>