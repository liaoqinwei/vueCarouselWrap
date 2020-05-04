### 使用方法
>1.导入carousel文件

代码使用
```html
<!--配置项
iHeight:容器的高度                                   auto
iWidth:容器的宽度                                    100%
elId:如果用户想在单页面使用多个需要传入一个唯一的id      
autoPlay:设置是否需要自动轮播                         false
moveRatio:在滑动时滑动的是当前容器多少的时候进入下一张   0.25
beginIndex:开始从哪一张轮播                           0
interval:自动轮播切换的间隔时间                        2000

-->
<carousel :elId="1" v-if="this.banners" :autoPlay="true">
  <carousel-item v-for="item in banners">
    <a :href="item.link" class="carousel-item-box">
      <img :src="item.image" :title="item.title" width="100%">
    </a>
  </carousel-item>
</carousel>
```
