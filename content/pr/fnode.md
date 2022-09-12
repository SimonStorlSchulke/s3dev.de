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
weight: 10
---

{{< project id="fnode" name="Nodebasierte Prozessautomatisierung" apps="C#, Godot" gh="SimonStorlSchulke/FNode" exe="https://github.com/SimonStorlSchulke/FNode/releases/latest">}}

FNode ist ein Nodebasiertes Tool für automatisiertes Dateimanagement und visuelle Programmierung. Anhand von logisch verknüpften Bausteinen können komplexe Aktionen programmiert und auf beliebige Dateien angewandt werden.

{{< image src="/pr/image/fnode_transp.png" title="Nodes">}}

**Anhand von logisch verknüpften Nodes bietet FNode unter anderem folgende Features**
- Automatisierte Verarbeitung großer Dateimengen
- Auslesung von Online APIs zur Nutzung im Nodetree
- Dateioperationen (Umbenennen, Verschieben, Kopieren, Textdateien erstellen etc.)
- Konvertierung von Bilddateien anhand dynamischer Regeln und einfache Batch-Prozesse für Bilddateien
- parallele bearbeitung beliebig vieler Nodetrees

<br>

Einfaches Videobeispiel, bei dem alle PNG Dateien in einem Ordner zu WebP konvertiert werden.

<video width="100%" muted controls>
  <source src="/pr/res/fnode-1.webm" type="video/mp4">
</video>

<br><br>

## Aber warum?

{{<twoculumn>}}
{{<left 48>}}
Bei meiner Arbeit bei yoose3D müssen wir oft mit großen Mengen an Dateien hantieren. Animationen werden zum Beispiel als mehrere Layer an Bildsequenz gerendert und später zum finalen Video zusammengefügt. Um repetitive Dateimanagement-Aufgaben zu automatisieren, baute ich das Tool **[y3D-FM (yoose3D File Manager)](https://github.com/SimonStorlSchulke/y3D-FM)**, das anhand vorgegebener Regeln Dateien umbenennt, verschiebt und Bildverarbeitungen durchführt.  
Da das Tool jedoch speziell auf Aufgaben bei yoose3D zugeschnitten war und zudem jedes weitere Feature die UI weiter verbaute, kam mir der Wunsch nach einem generellerem Tool für automatisiertes Dateimanagement. Da ich selbst sehr gerne Nodebasiert arbeite, sah ich mich nach Nodebasierten Tools dafür um und wurde nicht fündig.  
Da ich mich schon lange mit dem parsen von NodeTrees befassen wollte, baute ich also selbst eines.
{{</left>}}
{{<right 48>}}

{{< image src="/pr/image/fnode/y3d-fm.png" title="y3d-fm">}}

*y3d-FM Renaming und Batch-Processing Tool für yoose3D*

{{</right>}}
{{</twoculumn>}}

<br><br>
## Weitere Beispiele

{{< image src="/pr/image/fnode/thumbnailgenerator.png" title="Thumbnailgenerator">}}

*Thumbnailgenerator, der aus allen eingespeisten Bildern quadratische Thumbnails generiert. Viele Nodes und Inputs sind direkt in der Software per Maus-Hint dokumentiert.*
<br><br><br>

{{< image src="/pr/image/fnode/folderinfo.png" title="Folderinfo">}}

*NodeTree, um eine Textdatei mit Informationen über einen Ordner zu erstellen.*

<br>

## Download
Die aktuellste Version (aktuell nur Windows) kann <a href="https://github.com/SimonStorlSchulke/FNode/releases/latest">hier bei Github</a> heruntergeladen werden.

{{< /project >}}

<style>
  .project-summary h1 {
    font-size: 38px;
  }

  .project-summary img {
  }
</style>
