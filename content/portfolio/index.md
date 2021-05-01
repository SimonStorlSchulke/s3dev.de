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

/* Create four equal columns that sits next to each other */
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

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}
</style>

<div class="row">
  <div class="column">
    {{< image src="image/wursti.jpg" title="wursti" >}}
    {{< image src="image/menger.jpg" title="Menger" >}}
  </div>
  <div class="column">
    {{< image src="image/bike.jpg" title="Cool Bike" >}}
    {{< image src="image/candles.jpg" title="candles" >}}
    {{< image src="image/forest.jpg" title="Forest" >}}
  </div>
  <div class="column">
    {{< image src="image/camera.jpg" title="Camera" >}}
    {{< image src="image/k2so.jpg" title="" >}}
    {{< image src="image/trumpet.jpg" title="" >}}
  </div>
  <div class="column">
    {{< image src="image/underwater.jpg" title="" >}}
    {{< image src="image/mars.jpg" title="" >}}
  </div>
</div>
