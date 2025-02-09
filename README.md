<div align="center">
  <img src="https://komarev.com/ghpvc/?username=gucio321&color=blue&style=for-the-badge" alt="Profile Views counter" width=450px />
  <img src="https://github-readme-stats.vercel.app/api?username=gucio321&theme=blue-green&bg_color=90,137c15,175a71&title_color=fff&text_color=fff&count_private=true&show_icons=true&custom_title=Stats%20of%20gucio321%20aka%20M.Sz.&hide_border=true" width=450px alt="My GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gucio321&theme=blue-green&bg_color=90,175a71,137c15&title_color=fff&text_color=fff&count_private=true&show_icons=true&custom_title=Top%20Languages%20of%20gucio321&hide_border=true" width=450px alt="Top Languages"/>
  <hr>
  <img src="https://dcbadge.vercel.app/api/shield/694161855765151744?theme=discord-inverted" alt="Ping me on Discord!" width=450px />
</div>
 
<h1 align="center">What am I working on</h1>

Hi! \
My name is Maciej. I'm a student on the [AGH University of Krakow](https://agh.edu.pl/en/) university.

The most important things I'm currently working on:
- [giu](https://github.com/AllenDang/giu) development.
GIU is a nice golang framework - wrapper of <a href="https://github.com/AllenDang/cimgui-go">cimgui-go</a>
that is <a href="https://github.com/ocornut/imgui">Dear ImGUI</a>'s implementation 
in <a href="https://go.dev">golang</a>.
- [cimgui-go](https://github.com/AllenDang/cimgui-go) is also one of projects I'm working with.
This binding is auto-generated, so its extremely easy to keep up with the newest code from Dear ImGui.
Unfortunatley generator's code still needs improvements.
- If you're a High-School student from Poland, I'd also want to check out my
<a href="https://gucio321.github.io/fizyka">website with physics exercises</a>.
Let me know what do you think about it! Also, if you're interessted in
re-activating the website or contributing to it, post
<a href="https://github.com/gucio321/fizyka/discussions/5">In a discussion here</a>!
- Recently I've also added a chapter for my collage course on the previously mentioned website.
- I'v ealso launched a new website for advanced math course. [See here](https://gucio321.github.io/matematyka).

# Timeline

<table>
<tr>
<td>Time<td>Description
<tr><td>

05.11-13.06.2020 OpenDiablo2 projects

<td>

The first project I contributed to was (currently archived)
[OpenDiablo2](https://github.com/OpenDiablo2/OpenDiablo2). 
Thats where I lerned golang and, in fact, how to write code.
I lerned `git` basics and chose my first code editor - VIM
with the amazing extension [vim-go](https://github.com/fatih/vim-go).

My work on OpenDiablo2 ended when the maintainer of the project
decided to hold work on it and completely change our approach to
the project. Thats how
[AbyssEngine (go)](https://github.com/OpenDiablo2/AbyssEngine)
was started but never finished. Now OpenDiablo2 team worked on a C++
implementation of [Abyss Engine](https://github.com/AbyssEngine/AbyssEngine) for a while, but
after some time the project collapsed annd the team was disbanded.

<tr><td>

13.01-31.07.2021 HellSpawner

<td>

[HellSpawner](https://github.com/OpenDiablo2/HellSpawner)
was intented to be a toolchain for OpenDiablo2 project.
It used reverse-enginered libraries from OpenDiablo2 to display content of
game files.
HellSpawner was discontinued for some unspecified reason.

<tr><td>

10.05.2021-07.03.2022
Diablo II Save files  
parser and editor. 

<td>

[d2d2s](https://github.com/gucio321/d2d2s) was my presonal initiative.
It is a Diablo II Save Files
parser. After some time I've decided to write editor for that. Some parts
of this project are not finished yet.
This project helped me improve my reverse-engineering skills as well as
data manipulation in GO. Whats interessting is that many of things in the format
were written in bit-aligned fields, and GO is not adjusted for these type of
data, so I've also learned how to use bit operator `<<`, `>>`.

<tr><td>

10.03.2021 until now
GIU - UI Framework
for GO

<td>

The major HellSpawner's dependency (responsible for UI stuff) was [giu](https://github.com/AllenDang/giu).
At the beginning of my contribution
I was mainly adding improvements related to my HellSpawner work. But when
Hell Spawner collapsed, I've decided to start more active development in
giu.
After the author of giu - [@AllenDang](https://github.com/ALlenDang) started
the cimgui-go project, I did a migration of giu from
[imgui-go](https://github.com/inkyblackness/imgui-go) to cimgui-go
Now I'm a paintainer of giu.

<tr><td>

27.10.2021 - 18.06.2022 - sCHEMe computer game.

<td>

With a group of friends I've participated in a competition called
Turniej Trójgamiczny. We've created a game called [sCHEMe](https://scheme.noip.pl).

<tr><td>

01.06.2022 until now
cimgui-go - Dear ImGui wrapper for go

<td>

Since December 31 2022, [cimgui-go](https://github.com/AllenDang/cimgui-go)
is the only developed [Dear ImGui](https://github.com/ocornut/imgui)
wrapper for go.
I'm a maintainer of this project too.

During its development, I've learned many interessting things
about C++, C and cgo itself. I've also implemented converting
go closures to C callbacks "convertion" (Which I hope noone used earlier).

</table>

# Scientific work / research.

A sa student on [AGH UST](https://agh.edu.pl) I've also participated in some
project of a scientific nature. Here are some of them:

<table>
<tr><td>
06.12.2024
<td>
I wrote a paper on the topic of Potential Barrier, Tuneling and Reflection mechanism. <a href="https://github.com/gucio321/potential-barrier-solution">source code and pdf</a>.
<tr><td>
01.10.2024-20.11.2024 - <a href="https://github.com/gucio321/spiffy">Spiffy - SVG to GCode converter</a>
<td>
As a part of <a href="https://dss.agh.edu.pl/organizacje-studenckie/grant-rektora/edycja-2024) my science club [PROMAT](http://promat.agh.edu.pl) created a "Point Incremental Forming" machine [read more about that technology](https://www.sciencedirect.com/topics/engineering/point-incremental-forming">GR24</a>.
I was responsible for SVG to GCode converter. The project was written in Go and uses <a href="https://inkscape.org/">inkscape</a>'s API for some pre-processing. This project also contains a small visualisation app using <a href="https://ebitengine.org">Ebiten</a>.
</table>
