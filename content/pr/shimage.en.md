---
title: "Shimage"
tags: ["programming"]
summary: "Shaderbased image editor with C# and Godot"
thumbnail: "thumbs/image-editor.jpg"
apps: "C#, GLSL, Godot"
gradientcolor: "aqua"
featured": true
weight: 30
---

{{< project id="godot-image-edit" name="Shimage" gh="SimonStorlSchulke/Shimage/tree/Layers-Rewrite" exe="https://github.com/SimonStorlSchulke/Shimage/releases/tag/alpha04" apps="C#, GLSL, Godot">}}

{{<twoculumn>}}
{{<left 38>}}
A simple image editor with C# and Godot, based on a non-destructive filter stack. The filters work shader based in realtime. The GLSL shader code is generated from the filter stack at runtime.
{{</left>}}
{{<right 58>}}

<video width="100%" autoplay muted loop  controls>
  <source src="../res/image_edit.mp4" type="video/mp4">
</video> 

{{</right>}}
{{</twoculumn>}}

## Layers Rewrite
Currently I am rebuilding the software to handle multiple layers and projects at the same time. It should be possible to add different layer types (image files, shapes, text elements...) and assign filters and masks to each layer. The project is very complex, but the basic principle already works.

{{< image src="/pr/image/shimage_layers.jpg" title="Maki">}}

*My dog Maki "retouched" in the Layers rewrite branch.*



{{< /project >}}