---
title: "Portfolio"
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
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

.lg-sub-html {
  display: none;
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
    {{< image src="image/underwater.jpg" title="Deep Sea Discovery" >}}
    {{< image src="image/menger.jpg" title="Menger" >}}
  </div>
  <div class="column">
    {{< image src="image/bike.jpg" title="Cool Bike" >}}
    {{< image src="image/candles.jpg" title="candles" >}}
    {{< image src="image/forest.jpg" title="Forest" >}}
  </div>
  <div class="column">
    {{< image src="image/camera.jpg" title="Camera" >}}
    {{< image src="image/k2so.jpg" title="K2SO cleaning the Death Star" >}}
    {{< image src="image/trumpet.jpg" title="Trumpet" >}}
  </div>
  <div class="column">
    {{< image src="image/wursti.jpg" title="Wursti" >}}
    {{< image src="image/mars.jpg" title="Life on Mars?" >}}
  </div>
</div>
