+++
title = "Skills"
slug = "skills"
+++

# Software

<div style="float: left;">
<div class="responsive" style="background-image: url('./img/modeling.png');">
 <h2>3D Modeling</h2>


![blender](./appicons/blender.png)
![3DS Max](./appicons/3dsmax.png)

</div>

<div class="responsive" style="background-image: url('./img/rendering.png');">
 <h2>Lookdev. & Rendering</h2>

![blender](./appicons/blender.png)
![V-Ray](./appicons/vray.png)
![Renderman](./appicons/renderman.png)
![Luxcore](./appicons/luxcore.png)
![Arnold](./appicons/arnold.png)
</div>


<div class="responsive" style="background-image: url('./img/materials.png');">
 <h2>Komplexe Nodebasierte Materialien </h2>


![blender](./appicons/blender.png)
![V-Ray](./appicons/vray.png)
</div>

<div class="responsive" style="background-image: url('./img/rigging.png');">
 <h2>Rigging & Animation</h2>

![3DS Max](./appicons/3dsmax.png)
</div>

<div class="responsive" style="background-image: url('./img/compositing.png');">
 <h2>Compositing</h2>

![The Foundry Nuke](./appicons/nuke.png)
![Blackmagicdesign Fusion](./appicons/fusion.png)
</div>

<div class="responsive">

 <h2>Bildbearbeitung</h2>

![Affinity Photo](./appicons/affinity.png)
![Adobe Photoshop](./appicons/ps.png)
![Gimp](./appicons/gimp.png)
</div>

<div class="responsive" style="margin-bottom: 40px">
 <h2>Videobearbeitung</h2>

![DaVinci Resolve](./appicons/resolve.png)
![Adobe Premiere](./appicons/premiere.png)
</div>
</div style="float: left;">

<h1>Programmierung</h1>

<br>

<div>
<div class="responsive">
<h2>Allgemein</h2>

![C#](./appicons/cs.png)
![Java](./appicons/java.png)
![Golang](./appicons/go.png)
![C++](./appicons/c++.png)
![Git](./appicons/git.png)
</div>

<div class="responsive">
<h2>Scripting</h2>

![Python](./appicons/python.png)
</div>

<div class="responsive">
<h2>Webentwicklung</h2>

![Typescript](./appicons/typescript.png)
![Javascript](./appicons/javascript.png)
![HTML](./appicons/html.png)
![CSS](./appicons/css.png)
![Golang](./appicons/go.png)
</div>

<div class="responsive">
<h2>Spieleentwicklung</h2>

![Unity](./appicons/unity.png)
![Godot](./appicons/godot.png)
</div>

<div class="responsive">
<h2>Shader Entwicklung</h2>

![GLSL](./appicons/opengl.png)
</div>

<div class="responsive">
<h2></h2>
</div>
</div>

<script>

a = document.getElementsByClassName('responsive')
for (i in a){
   a[i].onmouseover=function(){console.log("a");}
   a[i].onmouseout=function(){/* code goes here */}
}

</script>

<style>
.page {
    width: 90%;
    max-width: 100%;
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


@media only screen and (max-width: 900px) {
  .responsive {
    width: 33.333%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}


@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
</style>
