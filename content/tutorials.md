---
title: "Tutorials"
date: 2021-04-27T11:46:11+02:00
lightgallery: false
heroimage: "/img/hero-placeholder.jpg"
---

<style>
.page {
  text-align: center;
}

.clickdetector {
  width: 392px;
  height: 220px;
  background: #f00a;
  position: absolute;
  pointer-events: none;
}

.youtubecard {
  box-shadow: 4px 5px 16px rgba(0, 0, 0, 0.671);
  margin: 10px;
  text-align: left;
  width: 392px;
  max-width: 90%;
  display: inline-block;
  max-height: fit-content;
  height: 420px;
  text-overflow: ellipsis;
  overflow: hidden;
  background-color: #1b1b1b;
}

.youtubecard h3 {
  display: absolute;
  margin-left: -12px !important;
  padding: 3px 8px 3px 0px;
  color: #fff;
  transition: color 1.6s, background-color .5s;
}

.youtubecard-bottom {
  padding: 10px;
}
.youtubecard h3 {
  margin: 0px 0px 10px 0px !important;
}
</style>

{{< youtubecard id="94eYd_cldtw" title="Using Color Ramps with light sources " description="In this tutorial, I explain how we can use the Light Falloff node, to create a nice colorful gradient for Lights in Blender.">}}
{{< youtubecard id="2LFQtdVct84" title="Advanced random object color variation " description="How to achieve better random color variation.">}}
{{< youtubecard id="cMUTOIhxfXU" title="Variety Nodepack #1 - Textures" description="Explaining all the Node-Groups in the Variety Nodepack I published on Gumroad.">}}
{{< youtubecard id="rvtxsARtxZs" title="Variety Nodepack #2 - Materials " description="Explaining all the Node-Groups in the Variety Nodepack I published on Gumroad.">}}
{{< youtubecard id="PICr70TPadU" title="Increasing the dynamic range of Environment Maps in Blender" description="How to convert JPG, PNG... Environment Maps to EXR and add High Dynamic Range for better HDRI lighting.">}}
{{< youtubecard id="7IXBOmimwbg" title="Mountain scene in Blender" description="A quick tutorial on how to create a nordic mountain scene in Blender and Gimp.">}}

<script defer>
const vids = document.querySelectorAll(".clickdetector");
console.log(".clickdetector");
console.log(vids);

vids.forEach(el => {
  el.onclick = function() {
    el.classList.add("in-view");
    console.log("aa");
};
});
</script>
