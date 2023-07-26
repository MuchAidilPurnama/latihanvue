<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://cdna.lystit.com/photos/lozuri/cfd8239f/balenciaga--Tape-Logo-Jacket.jpeg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://www.byrdie.com/thmb/ALOJJRFm3rVKd_OpGS0ICsnp6oM=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/GettyImages-1383020826-875017c317fe44268eb6ac31994e1a16.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://cdn.yoox.biz/12/12181325bw_13_l.jpg',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://i.pinimg.com/originals/3e/a0/45/3ea045d59a3cd620761e95c79d67fd78.jpg',
    'alt': 'Picture 4',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>