---
title: "FNode"
heroimage: "/img/hero/fnode.jpg"
lightgallery: true
---

{{< project id="fnode" name="Nodebasierte Prozessautomatisierung" apps="C#, Godot" gh="SimonStorlSchulke/FNode" exe="https://github.com/SimonStorlSchulke/FNode/releases/latest">}}

FNode ist ein Nodebasiertes Tool für automatisiertes Dateimanagement und visuelle Programmierung.

**Anhand von logisch verknüpften Nodes bietet FNode unter anderem folgende Features**
- Automatisierte Verarbeitung großer Dateimengen
- Auslesung von Online APIs zur Nutzung im Nodetree
- Dateioperationen (Umbenennen, Verschieben, Kopieren, Textdateien erstellen etc.)
- Konvertierung von Bilddateien anhand dynamischer Regeln und einfache Batch-Prozesse für Bilddateien
- parallele bearbeitung beliebig vieler Nodetrees

{{< image src="../image/fnode_transp.png">}}

Bei meiner Arbeit bei yoose3D müssen wir oft mit großen Mengen an Dateien hantieren. Animationen werden zum Beispiel als mehrere Layer an Bildsequenz gerendert und später zum finalen Video zusammengefügt. Um repetitive Dateimanagement-Aufgaben zu automatisieren, baute ich das Tool [y3D-FM (yoose3D File Manager)](https://github.com/SimonStorlSchulke/y3D-FM), das anhand vorgegebener Regeln Dateien umbenennt, verschiebt und Bildverarbeitungen durchführt.  
Da das Tool jedoch speziell mit den Aufgaben bei yoose3D 

{{< /project >}}

<style>
  .project-summary h1 {
    font-size: 38px;
  }
</style>
