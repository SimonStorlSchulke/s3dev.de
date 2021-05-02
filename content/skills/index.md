+++
title = "Skills"
slug = "skills"
+++

## Produktion

<div style="float: left;">

<a href="../projects/#saba">
<div class="responsive bg-img-modeling" style="background-image: url('./image/modeling.jpg');">
 <h2>3D Modeling</h2>

<div class="responsive-inner">

![blender](./appicons/blender.png)
![3DS Max](./appicons/3dsmax.png)

</div>
</div>
</a>

<a href="../demoreel">
<div class="responsive bg-img-lookdev" style="background-image: url('./image/rendering.jpg');">
 <h2>Lookdev. & Rendering</h2>

<div class="responsive-inner">

![Blender](./appicons/blender.png)
![V-Ray](./appicons/vray.png)
![Renderman](./appicons/renderman.png)
![Luxcore](./appicons/luxcore.png)
![Arnold](./appicons/arnold.png)

</div>
</div>
</a>


<div class="responsive bg-img-nodes" style="background-image: url('./image/materials.jpg');">
 <h2>Komplexe Nodebasierte Materialien </h2>

<div class="responsive-inner">

![blender](./appicons/blender.png)
![V-Ray](./appicons/vray.png)

</div>
</div>

<div class="responsive bg-img-rigging" style="background-image: url('./image/rigging.jpg');">
 <h2>Rigging & Animation</h2>

<div class="responsive-inner">

![Blender](./appicons/blender.png)
![3DS Max](./appicons/3dsmax.png)

</div>
</div>

<a href="../demoreel">
<div class="responsive bg-img-compositing" style="background-image: url('./image/compositing.jpg');">
 <h2>Compositing</h2>

<div class="responsive-inner">

![The Foundry Nuke](./appicons/nuke.png)
![Blackmagicdesign Fusion](./appicons/fusion.png)

</div>
</div>
</a>

<div class="responsive bg-img-image" style="background-image: url('./image/image_editing.jpg');">

 <h2>Bildbearbeitung</h2>

<div class="responsive-inner">

![Affinity Photo](./appicons/affinity.png)
![Adobe Photoshop](./appicons/ps.png)
![Gimp](./appicons/gimp.png)

</div>
</div>

<a href="../demoreel">
<div class="responsive bg-img-video" style="background-image: url('./image/video.jpg');">
 <h2>Videobearbeitung</h2>

<div class="responsive-inner">

![DaVinci Resolve](./appicons/resolve.png)
![Adobe Premiere](./appicons/premiere.png)

</div>
</div>
</a>

<a href="../music">
<div class="responsive bg-img-music" style="margin-bottom: 40px; background-image: url('./image/music.jpg');">
 <h2>Musikproduktion</h2>

<div class="responsive-inner">

![FL Studio](./appicons/fl.png)
![LMMS](./appicons/lmms.png)

</div>
</div>
</a>

</div>

## Programmierung

<div>

<a href="../projects/#fudge">
<div class="responsive bg-img-programming" style="background-image: url('./image/programming.jpg');">
<h2>Allgemein</h2>

<div class="responsive-inner">

![C#](./appicons/cs.png)
![Java](./appicons/java.png)
![Golang](./appicons/go.png)
![C++](./appicons/c++.png)
![Git](./appicons/git.png)

</div>
</div>
</a>

<a href="../projects/#evalgo">
<div class="responsive bg-img-webdev" style="background-image: url('./image/webdev.jpg');">
<h2>Webentwicklung</h2>

<div class="responsive-inner">

![HTML](./appicons/html.png)
![CSS](./appicons/css.png)
![Javascript](./appicons/javascript.png)
![Typescript](./appicons/typescript.png)
![Golang](./appicons/go.png)
![hugo](./appicons/hugo.png)

</div>
</div>
</a>

<div class="responsive bg-img-scripting" style="background-image: url('./image/scripting.jpg');">
<h2>Scripting</h2>

<div class="responsive-inner">

![Python](./appicons/python.png)
![CSS](./appicons/blender.png)

</div>

</div>

<a href="../projects/#cat">
<div class="responsive bg-img-gamedev" style="background-image: url('./image/gamedev.jpg');">
<h2>Spieleentwicklung</h2>

<div class="responsive-inner">

![Unity](./appicons/unity.png)
![Godot](./appicons/godot.png)

</div>
</div>
</a>

<a href="../projects/#thesis">
<div class="responsive bg-img-shading" style="background-image: url('./image/shading.jpg');">
<h2>Shader Entwicklung</h2>

<div class="responsive-inner">

![GLSL](./appicons/opengl.png)
![OSL](./appicons/osl.png)
![Unity PBR Graph](./appicons/unity.png)

</div>
</div>
</a>

</div>

<style>
  .page {
    width: 90%;
    max-width: 100%;
    max-width: 2200px;
}   

* {
  box-sizing: border-box;
}

img {
  position: absolute;
    bottom: 16px;
    filter: saturate(100%);
    width: 32px;
}
img:nth-of-type(2) {left: 50px;}
img:nth-of-type(3) {left: 84px;}
img:nth-of-type(4) {left: 118px;}
img:nth-of-type(5) {left: 152px;}
img:nth-of-type(6) {left: 186px;}

.responsive {
  color: #eee;
  text-shadow: 2px 2px 4px #111;
  background: #222;
  margin: 8px;
  padding: 0px 16px;
  float: left;
  width: 24%;
  height: 150px;
  position: relative;
  text-align: bottom;
  background-size: cover;
  box-shadow: 2px 2px 13px 5px rgba(0, 0, 0, 0.2);
}

.responsive-inner {
  visibility: hidden !important;
}

.responsive:hover .responsive-inner {
  visibility: visible !important;
}



@media only screen and (max-width: 1300px) {
  .responsive {
    width: 46%;
    margin: 6px 6px;
  }
}

@media only screen and (max-width: 680px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}

.bg-img-modeling:hover {
  background-image: url('./image/modeling_hover.jpg') !important;
}

.bg-img-lookdev:hover {
  background-image: url('./image/rendering_hover.jpg') !important;
}

.bg-img-nodes:hover {
  background-image: url('./image/materials_hover.jpg') !important;
}

.bg-img-rigging:hover {
  background-image: url('./image/rigging_hover.jpg') !important;
}

.bg-img-compositing:hover {
  background-image: url('./image/compositing_hover.jpg') !important;
}

.bg-img-image:hover {
  background-image: url('./image/image_editing_hover.jpg') !important;
}

.bg-img-video:hover {
  background-image: url('./image/video_hover.jpg') !important;
}

.bg-img-music:hover {
  background-image: url('./image/music_hover.jpg') !important;
}

.bg-img-programming:hover {
  background-image: url('./image/programming_hover.jpg') !important;
}

.bg-img-webdev:hover {
  background-image: url('./image/webdev_hover.jpg') !important;
}

.bg-img-scripting:hover {
  background-image: url('./image/scripting_hover.jpg') !important;
}

.bg-img-gamedev:hover {
  background-image: url('./image/gamedev_hover.jpg') !important;
}

.bg-img-shading:hover {
  background-image: url('./image/shading_hover.jpg') !important;
}

</style>
