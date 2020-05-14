<template>
  <div id="app">
    <carousel :iHeight="'auto'" :iWidth="'100%'" :elId="1" :autoPlay="false">
      <carousel-item>
        <a href="https://www.baidu.com" class="carousel-item-box">
          <img src="~assets/img/1.jpg" width="100%">
        </a>
      </carousel-item>
      <carousel-item>
        <a href="" class="carousel-item-box">
          <img src="~assets/img/2.jpg" width="100%">
        </a>
      </carousel-item>
      <carousel-item>
        <a href="" class="carousel-item-box">
          <img src="~assets/img/3.jpg" width="100%">
        </a>
      </carousel-item>
      <carousel-item>
        <a href="" class="carousel-item-box">
          <img src="~assets/img/4.jpg" width="100%">
        </a>
      </carousel-item>
    </carousel>
  </div>
</template>

<script>
  import {Carousel, CarouselItem} from "components/carousel/index.js"

  export default {
    name: 'App',
    components: {
      Carousel,
      CarouselItem
    }
  }
</script>

<style>
  @import "~assets/css/reset.min.css";


</style>
