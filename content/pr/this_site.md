---
title: "Diese Website"
lightgallery: true
tags: ["webdev"]
summary : "Umsetzung dieser Webseite mit HUGO."
thumbnail : "thumbs/website.png"
apps : "HUGO, HTML, CSS, JS"
gradientcolor : "green"
featured: false
---

{{< project id="cat" name="Diese Website" apps="HUGO, HTML, CSS, JS">}}

<!--<canvas id="canvas" style="width: 100%;"></canvas>-->

<img class="ig" src="../image/website.png" width="11%"/>
<img class="ig" src="../image/website.png" width="16%"/>
<img class="ig" src="../image/website.png" width="23%"/>
<img class="ig" src="../image/website.png" width="31%"/>
<img class="ig" src="../image/website.png" width="42%"/>
<img class="ig" src="../image/website.png" width="56%"/>
<img id="limg" class="ig" src="../image/website.png" width="75%"/>
<img style = "box-shadow: 0px 0px 60px #0007;" class="ig" src="../image/website.png" width="100%">

<div class="spacer" style="height: 900px;"></div>

Diese Webseite wurde mit [Hugo](https://gohugo.io/) und dem sehr stark modifiziertem [LoveIt Theme](https://hugoloveit.com/) umgesetzt!

 HUGO ist als Generator statischer Seiten hervorragend für große und kleine Projekte als Ersatz für klassische CMS Systeme geeignet. Das hat den Vorteil, dass kein System im Backend benötigt wird. Alles wird lokal in Millisekunden aus den Quelldateien generiert und als statische Seiten auf den Server gespiegelt.

{{< /project >}}

<script defer>

const af = document.querySelectorAll(".ig");
const ig = document.querySelector(".ig");
const spacer = document.querySelector(".spacer");

function parallax() {
  let offsety = 0;

  for (let i = 0; i < af.length; i++) {
    const el = af[7-i];
    const val = el.offsetHeight;
    let aspect = ig.offsetWidth / window.innerWidth;
    el.style.transform = `translate(-50%, ${offsety}px)`;
    offsety += val * 0.214 * (1-(window.scrollY / 1000));
  }

  spacer.style.height = spacer.offsetWidth * 0.70+"px";
}

parallax();

document.querySelector("#limg").addEventListener('load', parallax);
window.addEventListener("scroll", parallax);
window.addEventListener("resize", parallax);

</script>

<style>

.ig {
  position: absolute;
  left: 50%;
  transform: translate(-50%, 0);
}

</style>
