<template>
  <div>
    <NavbarComponent></NavbarComponent>
    <br>
    <Header></Header>
    <br>
    <h1 align="center" style="color: black;" class="font-mono m-2">Varsicy Jacket</h1>
    <SidebarComponent></SidebarComponent>
    <br>
    <h1 align="center" style="color: black;" class="font-mono m-2">Hoodie Balenciaga</h1>
    <ContentPage></ContentPage>
    <br>
    <h1 align="center" style="color: black;" class="font-mono m-2">Sepatu Adidas</h1>
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