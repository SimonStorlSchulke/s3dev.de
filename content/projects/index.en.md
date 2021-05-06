---
title: "Projects"
date: 2021-04-26T23:27:14+02:00
lightgallery: true
heroimage: "/img/hero-placeholder.jpg"
---

<div class="sidebar">
  <a href="#fudge">FUDGE</a>
  <a href="#evalgo">Evalgo</a>
  <a href="#rtcg">RTCG</a>
  <a href="#thesis">Clouds</a>
  <a href="#cat">A Cat in Time</a>
  <a href="#saba">SABA</a>
  <a href="#gamejams">GameJams</a>
  <i class="sidebar-arrow fas fa-chevron-left"></i>
</div>


{{< project id="fudge" name="FUDGE" gh="JirkaDellOro/FUDGE" apps="TypeScript, WebGL, HTML, CSS">}}
{{<twoculumn>}}
{{<left 48>}}
**F**urtwangen **U**niversity **D**idactic **G**ame **E**ditor is a TypeScript based Game Engine designed with education in mind by Prof. Jirka Dell'Oro-Friel. I worked on the implementation of mesh generation, OBJ mesh import and shaders. In the <a href="https://github.com/hs-furtwangen/FUDGE-Chemistry_MasterW19">Chemistry with FUDGE <i class="fab fa-github fa-gh"></i></a> project, we used the engine at a very early stage to implement an [atomic orbital construction kit](https://hs-furtwangen.github.io/FUDGE-Chemistry_MasterW19/app/tutor.html).

{{< image src="image/fcl2.jpg" linked="false" >}}


{{</left>}}
{{<right 48>}}
{{< image src="image/fcl.png" linked="false" >}}
{{</right>}}
{{</twoculumn>}}
{{< /project >}}
<hr>
{{< project id="evalgo" name="Evalgo" gh="SimonStorlSchulke/Evalgo" apps="Go, HTML, CSS, JavaScript">}}
Evalgo is a course management system for students and instructors that was developed for the course *Current Developments in Online Media* by Prof. Dirk Eisenbiegler on the topic Evaluation of Go for Web Development.

{{< image src="image/evalgo.png" title="Evalgo">}}
<br><br>

Instructors and tutors can write assignments and students can submit them.

{{< image src="image/evalgo3.png" title="Evalgo feedback">}}
<br><br>

Feedback and grades can be given by instructors on the submissions, which appear in an overview and grade table for authorized users.

{{< image src="image/evalgo2.png" title="Evalgo grade table">}}
{{< /project >}}
<hr>
{{< project id="rtcg" name="Realtime CG" gh="SimonStorlSchulke/RealtimeCG" apps="Go, OpenGL">}}

For the course *Real-Time Computer Graphics* by Rainer Duda I developed a demo about procedural textures and fractals using Go and OpenGL.

<video width="512px" autoplay muted loop>
  <source src="res/shading.mp4" type="video/mp4">
</video> 
{{< /project >}}
<hr>
{{< project id="thesis" name="Cloud Generation" pdf="res/Bachelorarbeit_Simon_Storl-Schulke.pdf" apps="OSL, Blender">}}

In my bachelor thesis I dealt with the **procedural generation of clouds in offline render engines**. The focus was on usability. With the help of a few parameters it should be possible to implement complex cloud shapes. The implementation was done with OSL (Open Shading Language).

<video width="100%" autoplay muted loop controls>
  <source src="res/thesis_example.mp4" type="video/mp4">
</video> 

{{< image src="image/thesis.jpg"title="Thesis - cloud parameters">}}
{{< /project >}}
<hr>
{{< project id="cat" name="A Cat in Time" apps="Unity, Blender">}}
Mobilegame for the [City Museum Tübingen](https://www.tuebingen.de/stadtmuseum/) (still in development). To save the ghost of the cat mummy we travel to the year 1607. Here I was responsible for 3D models and texturing, as well as music. The soundtrack has the special gimmic that the instruments change during the time shift.

{{< image src="image/ct.png" title="A Cat in Time">}}

*In Cooperation with Linus Ehmann (Programmierung), Tim Marquardt (conzept) and Olivia Storz (Design and Conzept)*
{{< /project >}}
<hr>
{{< project id="saba" name="SABA Scan" apps="Blender, Meshroom">}}

{{<twoculumn>}}
{{<left 46>}}

3D Scanning by drone and remodeling of the old SABA Farbik site in the Villingen Innovation Park in cooperation with Andreas Reich, Linus Ehmann and Sophie Tobisch. 

Among other things, I was responsible for the remodeling of the SABA main building based on the scanned data and references.

{{< image src="image/heizwerk.png" title="SABA heating plant">}}

{{</left>}}
{{<right 50>}}

{{< image src="image/saba2.png" title="SABA letters">}}
{{< image src="image/saba1.png" title="SABA main building">}}

{{</right>}}
{{</twoculumn>}}
{{< /project >}}
<hr>
{{< project id="gamejams" name="GameJams" apps="Unity, Godot, Blender, FL-Studio">}}

I participated in several GameJams during my studies. I took different roles - sometimes I was responsible for code, sometimes for 3D models and sometimes for music. So I was able to expand my knowledge in all areas and learn to work under strong time pressure in a team.

{{< image src="image/ibe.jpg" width="850px" caption="[**Inbound: Earth**](https://globalgamejam.org/2019/games/inbound-earth) | VR 360° Towerdefense Game. Satellites can be set to repel incoming alien spaceships from Earth. Here I was involved in programming and 3D models" title="Inbound: Earth">}}

{{< image src="image/dlab.jpg" width="850px" caption="[**Don't Lose a Beat**](https://github.com/CalvinDO/DontLoseABeat) | Bring a disharmonic orchestra back to the right beat and pitch. For this game I produced the music and helped with coding." title="Don't Lose a Beat">}}

{{< image src="image/fws.jpg" width="850px" caption="[**Fuwashima**](https://globalgamejam.org/2020/games/fuwashima-2) | VR game in which the player must solve puzzles to prevent an impending reactor disaster, but only makes it worse in the process. I was responsible for the 3D models" title="Fuwashima">}}

{{< image src="image/fox.jpg" width="850px" caption="**Foxgame** | A young fox searches for his mommy in the snow." title="Foxgame">}}

{{< /project >}}

<style>
  .page {
    width: 100%;
    max-width: 1400px !important;
    padding-right: 150px;
}

.shadow {
  box-shadow: 8px 5px 20px #1114;
}

@media screen and (max-width: 960px) {
    .page {
    width: 100%;
    max-width: 100% !important;
    padding-right: 50px;
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

.hero h1 {
  right: 160px;
}

</style>
