# Docking Station!
[View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/cec4245d48316d051146b3ca?renderMode=0&uiState=6a2cddf3cc68f1e0ff63f0b2)

A very cool laptop docking station with 9 USB-A 2.0 ports!

<div id="contents">

1. [Why?](#why)
2. [What can it do?](#what-can-it-do)
3. [Fallout Zine](#fallout-zine)

</div>

## Why?
My laptop only has 2 USB-A ports, which is honestly not enough especially when both of them are used up for a keyboard and mouse.

I made this docking station to change that.

Another reason I made this is that I kinda like taking my laptop with me and keep it on my lap while using it on the sofa sometimes, so a docking station kinda makes that easier so you only have to plug it in and then everything works!

<div align="center"><a href="#contents">Jump to contents</a></div>

## What can it do?
It has 9 USB ports, which you can connect whatever you want to. The USB ports are controlled using an Fe1.1s controller.

It also has an ESP32 and 2 controllable PWM case fans (with two mosfet so you can turn them completely off), to keep your laptop cool and prevent it from overheating.

I also added external power from a barrel jack, because the laptop wont be able to power so many USB ports, especially when things are connected to them.

There is also a programmable e-ink display, you can display the time, your notifications, the current speed of the fans, or even show specifically which USB ports are currently in use!

I also added a mini detachable macropad with three switches and a rotary encoder.

You can program the macropad's buttons to do whatever you want! The rotary encoder also works as a switch, so technically there are four switches. You can make the rotary encoder change the volume, fan speeds, etc!

The macropad is connected to the ESP32!

Oh and btw the ESP32 also supports WiFi incase you want it to show weather or something even when the laptop is turned off.

The ESP32 also knows exactly which ports are connected to devices at a time, so you can also make it show how many ports are in use, and how many are free, etc!

<div align="center"><a href="#contents">Jump to contents</a></div>


## Fallout Zine
<a href="https://github.com/KavyanshKhaitan2/docking-station/blob/main/zine/Zine%20Print.pdf"><img height="500" src="https://github.com/KavyanshKhaitan2/docking-station/blob/main/zine/Zine%20Preview.png?raw=true"></a>

[ [Download PDF](https://github.com/KavyanshKhaitan2/docking-station/raw/main/zine/Zine%20Print.pdf) ]

<div align="center"><a href="#contents">Jump to contents</a></div>

## PCB
<div align="center"><a href="https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FKavyanshKhaitan2%2Fdocking-station%2Ftree%2Fmain%2Fpcb%2F">View in KiCanvas</a></div>
