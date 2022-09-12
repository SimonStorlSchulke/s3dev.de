---
title: "Wolkengenerierung mit OSL"
lightgallery: true
tags: ["programming", "3d"]
summary: "Mithilfe weniger Parameter ist es möglich, komplexe Wolkenformen zu generieren"
thumbnail: "thumbs/cloud.jpg"
apps: "OSL, Blender"
gradientcolor: "blue"
featured": false
---

{{< project id="thesis" name="Wolkengenerierung mit OSL" pdf="../res/Bachelorarbeit_Simon_Storl-Schulke.pdf" gh="SimonStorlSchulke/OSL-Cloud-Generation" apps="OSL, Blender">}}

In meiner Bachelorthesis beschäftigte ich mich mit der **Prozeduralen Generierung von Wolken in Offline-Renderengines**. Der Fokus lag hierbei auf Anwenderfreundlichkeit. Mithilfe weniger Parameter soll es möglich sein, komplexe Wolkenformen umzusetzen. Der Prototyp wurde in Blender mit dessen Echtzeit Renderengine Eevee umgesetzt. Die Implementierung erfolgte dann mit OSL (Open Shading Language) und wurde mit der Cycles Renderengine getestet.

<video width="100%" autoplay muted loop controls>
  <source src="../res/thesis_example.mp4" type="video/mp4">
</video> 

{{< image src="/pr/image/thesis.jpg"title="Thesis - Wolkenparameter">}}
{{< /project >}}