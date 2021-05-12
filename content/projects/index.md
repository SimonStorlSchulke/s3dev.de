---
title: "Projects"
date: 2021-04-26T23:27:14+02:00
lightgallery: true
heroimage: "image/hero.jpg"
---

<div class="sidebar">
  <a href="#godot-image-edit">Image Editor</a>
  <a href="#fudge">FUDGE</a>
  <a href="#evalgo">Evalgo</a>
  <a href="#rtcg">RTCG</a>
  <a href="#thesis">Wolken</a>
  <a href="#cat">A Cat in Time</a>
  <a href="#saba">SABA</a>
  <a href="#gamejams">GameJams</a>
  <i class="sidebar-arrow fas fa-chevron-left"></i>
</div>

{{< project id="godot-image-edit" name="Image Editor" gh="SimonStorlSchulke/GodotPhotoEdit" exe="https://github.com/SimonStorlSchulke/GodotPhotoEdit/releases/tag/alpha02" apps="C#, GLSL, Godot">}}

{{<twoculumn>}}
{{<left 47>}}
Ein einfacher Bildeditor mit C# und Godot, basierend auf einem non-destruktiven Filter-Stack. Die Filter funktionieren mit Shadern in Echtzeit. Der Shadercode wird dabei zur Laufzeit aus dem Filterstack generiert.
{{</left>}}
{{<right 47>}}

<video width="720px" autoplay muted loop>
  <source src="res/image_edit.mp4" type="video/mp4">
</video> 

{{</right>}}
{{</twoculumn>}}



{{< /project >}}

<hr>

{{< project id="evalgo" name="Evalgo" gh="SimonStorlSchulke/Evalgo" apps="Go, HTML, CSS, JavaScript">}}

{{<twoculumn>}}
{{<left 48>}}
Evalgo ist ein Kurs-Management System für Studierende und Dozenten, dass für den Kurs *Aktuelle Entwicklungen im Bereich Online-Medien* von Prof. Dirk Eisenbiegler zum Thema *Evaluation von Go für Webdevelopment* entwickelt wurde.<br><br>
Dozenten und Tutoren können Aufgabenstellungen mit Markdown-Formatierung verfassen und Studierende diese abgeben. Auf der Hauptseite sind die Aufgabenstellung, sowie die Abgaben aller Studierenden zur ausgewählten Aufgabe zu finden. Je nach Konfiguration sind Letztere für alle User oder nur für authorisierte Nutzer (Dozent oder Tutor) sichtbar.
<br><br>
{{</left>}}
{{<right 48>}}
{{< image src="image/evalgo.png" title="Evalgo">}}
{{</right>}}
{{</twoculumn>}}
<br>

{{<twoculumn>}}
{{<left 48>}}
Zu den Abgaben können von Dozenten Feedback und Noten gegeben werden, die in einer Übersicht und Notentabelle für authorisierte Nutzer erscheinen. <br><br>
{{< image src="image/evalgo2.png" title="Evalgo Notentabelle">}}
{{</left>}}
{{<right 48>}}
{{< image src="image/evalgo3.png" title="Evalgo Feedback">}}

{{</right>}}
{{</twoculumn>}}

*Aus rechtlichen Gründen (User Generated Content) kann ich leider keine Beispielanwendung hosten.*

{{< /project >}}

<hr>

{{< project id="fudge" name="FUDGE" gh="JirkaDellOro/FUDGE" apps="TypeScript, WebGL, HTML, CSS">}}
{{<twoculumn>}}
{{<left 48>}}
**F**urtwangen **U**niversity **D**idactic **G**ame **E**ditor ist eine TypeScript basierte GameEngine speziell für die Lehre von Prof. Jirka Dell'Oro-Friedl. Hier arbeitete ich an der Implementierung von Meshgenerierung, OBJ-Meshimport und Shadern. Im Projekt <a href="https://github.com/hs-furtwangen/FUDGE-Chemistry_MasterW19">Chemistry with FUDGE <i class="fab fa-github fa-gh"></i></a> verwendeten wir die Engine in sehr frühen Stadium, um einen [Atom-Orbital-Baukasten](https://hs-furtwangen.github.io/FUDGE-Chemistry_MasterW19/app/tutor.html) umzusetzen.

{{< image src="image/fcl2.jpg" linked="false" >}}

{{</left>}}
{{<right 48>}}
{{< image src="image/fcl.png" linked="false" >}}
{{</right>}}
{{</twoculumn>}}
{{< /project >}}
<hr>

{{< project id="rtcg" name="Realtime CG" gh="SimonStorlSchulke/RealtimeCG" apps="Go, OpenGL">}}

Zum Kurs *Echtzeit Computergrafik* von Rainer Duda entwickelte ich hier mit Go und OpenGL eine Demo zum Thema prozedurale Texturen und Fraktale.

<video width="512px" autoplay muted loop>
  <source src="res/shading.mp4" type="video/mp4">
</video> 

{{< /project >}}
<hr>
{{< project id="thesis" name="Cloud Generation" pdf="res/Bachelorarbeit_Simon_Storl-Schulke.pdf" gh="SimonStorlSchulke/OSL-Cloud-Generation" apps="OSL, Blender">}}

In meiner Bachelorthesis beschäftigte ich mich mit der **Prozeduralen Generierung von Wolken in Offline-Renderengines**. Der Fokus lag hierbei auf Anwenderfreundlichkeit. Mithilfe weniger Parameter soll es möglich sein, komplexe Wolkenformen umzusetzen. Der Prototyp wurde in Blender mit dessen Echtzeit Renderengine Eevee umgesetzt. Die Implementierung erfolgte dann mit OSL (Open Shading Language) und wurde mit der Cycles Renderengine getestet.

<video width="100%" autoplay muted loop controls>
  <source src="res/thesis_example.mp4" type="video/mp4">
</video> 

{{< image src="image/thesis.jpg"title="Thesis - Wolkenparameter">}}
{{< /project >}}
<hr>
{{< project id="cat" name="A Cat in Time" apps="Unity, Blender">}}
Mobilegame für das [Stadtmuseum Tübingen](https://www.tuebingen.de/stadtmuseum/) (noch in Entwicklung). Um den Geist der Katzenmumie zu retten, reisen wir in das Jahr 1607. Der Spieler muss dabei in vier verschiedenen historischen Museumsräumen jeweils ein Rätsel lösen. Hier war ich für 3D-Modelle und Texturierung, sowie für Musik zuständig. Der [Soundtrack](/music/#a-cat-in-timeprojectscat--soundtrack) hat die Besonderheit, dass beim Zeitsprung die Instrumente wechseln.


{{< image src="image/ct.png" title="A Cat in Time">}}

*In Kooperation mit Linus Ehmann (Programmierung), Tim Marquardt (Konzept) und Olivia Storz (Design & Konzept)*

{{< /project >}}
<hr>
{{< project id="saba" name="SABA Scan" apps="Blender, Meshroom">}}

{{<twoculumn>}}
{{<left 46>}}

Einscannen per Drohne und Nachmodellierung des alten SABA Farbikgeländes im Innovationspark Villingen in Kooperation mit Andreas Reich, Linus Ehmann und Sophie Tobisch. 

Hierbei war ich u.a. für die Nachmodellierung des SABA Hauptgebäudes anhand der eingescannten Daten und Referenzen zuständig.

{{< image src="image/heizwerk.png" title="SABA Heizwerk">}}
{{</left>}}
{{<right 50>}}

{{< image src="image/saba2.png" title="SABA Schriftzug">}}

{{< image src="image/saba1.png" title="SABA Hauptgebäude">}}

{{</right>}}
{{</twoculumn>}}

{{< /project >}}
<hr>
{{< project id="gamejams" name="GameJams" apps="Unity, Godot, Blender, FL-Studio">}}

Ich nahm während meines Studiums an mehreren GameJams teil. Dabei nahm ich verschiedene Rollen ein - mal war ich für Code, mal für 3D-Modelle und mal für Musik zuständig. So konnte ich so meine Kenntnisse in allen Bereichen ausbauen und lernen unter starkem Zeitdruck im Team zu arbeiten.


{{< image src="image/ibe.jpg" width="850px" title="Inbound: Earth">}}

[**Inbound: Earth**](https://globalgamejam.org/2019/games/inbound-earth) | VR 360° Towerdefense Spiel. Sateliten können gesetzt werden, um ankommende Alien-Raumschiffe von der Erde abzuwehren. Hier war ich an Programmierung und 3D-Modellen beteiligt

{{< image src="image/dlab.jpg" width="850px" title="Don't Lose a Beat">}}

[**Don't Lose a Beat**](https://github.com/CalvinDO/DontLoseABeat) | Bringe ein durcheinanderspielendes Orchester wieder in den richtigen Takt und Tonlage. Hier sorgte ich für 3D-Modelle, Musik und half bei der Programmierung. Das Projekt entstand während des GlobalGamejams 2021 innerhalb von fünf Tagen. Der Rahmen war natürlich viel zu groß war für den kurzen Zeitraum und da ich für alle Modelle, Animationen und Musik verantwortlich war, sowie bei der Programmierung aushalf, ist beim Ergebnis die Spielbarkeit nur recht bedingt gegeben. Wir hatten trotzdem sehr viel positiven Stress und Spaß an der Sache.
<br><br>
{{< image src="image/fws.jpg" width="850px" title="Fuwashima">}}

[**Fuwashima**](https://globalgamejam.org/2020/games/fuwashima-2) | VR Spiel, in dem der Spieler Rätsel lösen muss, um eine drohende Reaktorkatastrophe zu verhindern, es dabei jedoch nur schlimmer macht. Hier war ich für die 3D-Modelle zuständig
<br><br>
{{< image src="image/fox.jpg" width="850px" title="Foxgame">}}

**Foxgame** | Ein junger Fuchs sucht seine Mama im Schnee. Mein erstes GameJam Spiel, in dem man noch nicht viel mehr tun kann, als die Welt zu erkunden.

{{< /project >}}

<style>
  .page {
    width: 100%;
    max-width: 1400px !important;
    padding-right: 120px !important;
}

.shadow {
  box-shadow: 8px 5px 20px #1114;
}

.lg-sub-html {
  display: none !important;
}

@media screen and (max-width: 960px) {
    .page {
    width: 100%;
    max-width: 100% !important;
    padding-right: 20px !important;
    }
}

h2 {
  margin-top: 42px !important;
  color: white !important;
  font-size: 40px !important;
}

hr {
  margin-top: 35px !important;
}

</style>
