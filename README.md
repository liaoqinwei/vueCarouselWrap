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
<carousel :iHeight="'auto'" :iWidth="'100%'" :elId="1" :autoPlay="true">
  <carousel-item>
    <a href="https://www.baidu.com" class="carousel-item-box">
      <img src="~assets/img/1.jpg" width="100%">
    </a>
  </carousel-item>
  <carousel-item>
    <a href=""  class="carousel-item-box">
      <img src="~assets/img/2.jpg" width="100%">
    </a>
  </carousel-item>
  <carousel-item>
    <a href=""  class="carousel-item-box">
      <img src="~assets/img/3.jpg" width="100%">
    </a>
  </carousel-item>
  <carousel-item>
    <a href=""  class="carousel-item-box">
      <img src="~assets/img/4.jpg" width="100%">
    </a>
  </carousel-item>
</carousel>
```
