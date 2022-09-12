---
title: "Shimage"
tags: ["programming"]
summary: "Shaderbasierter Bildeditor mit C# und Godot"
thumbnail: "thumbs/image-editor.jpg"
apps: "C#, GLSL, Godot"
gradientcolor: "aqua"
featured": true
weight: 30
---

{{< project id="godot-image-edit" name="Shimage" gh="SimonStorlSchulke/Shimage/tree/Layers-Rewrite" exe="https://github.com/SimonStorlSchulke/Shimage/releases/tag/alpha04" apps="C#, GLSL, Godot">}}

{{<twoculumn>}}
{{<left 38>}}
Ein einfacher Bildeditor mit C# und Godot, basierend auf einem non-destruktiven Filter-Stack. Die Filter funktionieren Shaderbasiert in Echtzeit. Der GLSL Shadercode wird dabei zur Laufzeit aus dem Filterstack generiert.
{{</left>}}
{{<right 58>}}

<video width="100%" autoplay muted loop  controls>
  <source src="../res/image_edit.mp4" type="video/mp4">
</video> 

{{</right>}}
{{</twoculumn>}}

## Layers Rewrite
Aktuell baue ich die Software um, um mehrere Layer und Projekte gleichzeitig zu bearbeiten. Es soll möglich sein, verschieene Layertypen (Bilddateien, Formen, Textelemente...) hinzuzufügen und jedem Layer Filter und Masken zuzuweisen. Das Projekt ist sehr komplex, aber das Grundprinzip funktioniert bereits.

{{< image src="/pr/image/shimage_layers.jpg" title="Folderinfo">}}

*Mein Hund Maki in der Layers-Rewrite-Branch "verschönert"*



{{< /project >}}