---
title: "FNode"
heroimage: "/img/hero/fnode.jpg"
lightgallery: true
tags: ["programming"]
summary: "Nodebasiertes Tool für automatisiertes Dateimanagement und visuelle Programmierung"
thumbnail: "thumbs/fnode.jpg"
apps: "C#, Godot"
gradientcolor: "aqua"
featured": true
---

{{< project id="fnode" name="Nodebasierte Prozessautomatisierung" apps="C#, Godot" gh="SimonStorlSchulke/FNode" exe="https://github.com/SimonStorlSchulke/FNode/releases/latest">}}

FNode ist ein Nodebasiertes Tool für automatisiertes Dateimanagement und visuelle Programmierung.

**Anhand von logisch verknüpften Nodes bietet FNode unter anderem folgende Features**
- Automatisierte Verarbeitung großer Dateimengen
- Auslesung von Online APIs zur Nutzung im Nodetree
- Dateioperationen (Umbenennen, Verschieben, Kopieren, Textdateien erstellen etc.)
- Konvertierung von Bilddateien anhand dynamischer Regeln und einfache Batch-Prozesse für Bilddateien
- parallele bearbeitung beliebig vieler Nodetrees

{{< image src="../image/fnode_transp.png" title="Nodes">}}

Bei meiner Arbeit bei yoose3D müssen wir oft mit großen Mengen an Dateien hantieren. Animationen werden zum Beispiel als mehrere Layer an Bildsequenz gerendert und später zum finalen Video zusammengefügt. Um repetitive Dateimanagement-Aufgaben zu automatisieren, baute ich das Tool [y3D-FM (yoose3D File Manager)](https://github.com/SimonStorlSchulke/y3D-FM), das anhand vorgegebener Regeln Dateien umbenennt, verschiebt und Bildverarbeitungen durchführt.  
Da das Tool jedoch speziell auf Aufgaben bei yoose3D zugeschnitten war und zudem jedes weitere Feature die UI weiter verbaute, kam mir der Wunsch nach einem generellerem Tool für automatisiertes Dateimanagement. Da ich selbst sehr gerne Nodebasiert arbeite, sah ich mich nach Nodebasierten Tools dafür um und wurde nicht fündig - also baute ich selbst eines.

{{< image src="../image/fnode.jpg" title="FNode">}}

{{< /project >}}

<style>
  .project-summary h1 {
    font-size: 38px;
  }
</style>
