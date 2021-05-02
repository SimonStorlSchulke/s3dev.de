---
title: "Renderings"
draft: false
lightgallery: true
---

<style>

.page {
    width: 90%;
    max-width: 100%;
}   

.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

.column {
  flex: 22%;
  max-width: 25%;
  padding: 0 4px;
  height: auto;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

.single .content figure {
    margin: 8px 0px;
}

.image-caption {
  display: none !important;
}

@media screen and (max-width: 1100px) {
  .column {
    flex: 32%;
    max-width: 32%;
  }
}

@media screen and (max-width: 800px) {
  .column {
    flex: 48%;
    max-width: 48%;
  }
}

@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}
</style>

<div class="row">
  <div class="column">
    {{< image src="image/underwater.jpg" title="" caption="Deep Sea Discovery" >}}
    {{< image src="image/menger.jpg" title="" caption="Menger Sponge" >}}
  </div>
  <div class="column">
    {{< image src="image/bike.jpg" title="" caption="Cool Bike" >}}
    {{< image src="image/candles.jpg" title="" caption="candles" >}}
    {{< image src="image/forest.jpg" title="Forest" caption="Forest" >}}
  </div>
  <div class="column">
    {{< image src="image/camera.jpg" title="" caption="Camera" >}}
    {{< image src="image/k2so.jpg" title="" caption="K2SO cleaning the Death Star" >}}
    {{< image src="image/trumpet.jpg" title="" caption="Trumpet" >}}
  </div>
  <div class="column">
    {{< image src="image/wursti.jpg" title="" caption="Adventure Wursti" >}}
    {{< image src="image/mars.jpg" title="" caption="Life on Mars?" >}}
  </div>
</div>
