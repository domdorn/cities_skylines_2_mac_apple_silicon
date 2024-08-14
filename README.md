# Cities: Skylines 2 on Mac / Apple Silicon


<h1>PROJECT DEAD - DONT USE ANYMORE!</h1>
Sadly, after newer patches (the first one after they introduced mods), I wasn't able anymore to get the game working.. sometimes at 
least the paradox boot logo came, sometimes not even that. Long story short: Its not working anymore. 

## Old content:

<strong>This repository is the approach to simplify getting *Cities Skylines 2* running on MacOS / Apple Silicon.</strong>

This repository should simplify the process and make it easier for others to get the game running on their Macs without many manual steps.

## Installation Instructions

1) Install [Whisky](https://github.com/Whisky-App/Whisky)
2) Start Whisky, Create a new Bottle
3) Using winetricks,
   4) install DotNet48 (Libraries),
   5) Install "all fonts"
   6) Install steam
7) Run steam, Login, Install cities skylines 2
8) After you have installed Cities Skylines 2, download this repository as ZIP File
9) Open your bundle in finder by clicking "Open C: Drive" in Whisky
10) Go to the parent directory of the c_drive by doing a cmd+click on the drive_c title in finder, then click on the folder with a long name like "7228B4F6-DFB2-4243-B445-507DC5755FB1" 
11) Copy the files in this repository over the existing files in the folder. (important to not accidentially delete the existing folders, just replace the files in the folders with the files in this repository.) 
12) Run the game

## What does this do?

1) already includes the `version.dll` fix
2) includes the correct Settings.coc to prevent the issue with volumetric fog
3) includes the `winhttp.dll` and [BepInEx 5.4.22](https://github.com/BepInEx/BepInEx/releases) for modding including correct configuration
4) includes the "[Traffic Lights Enhancement](https://github.com/slyh/Cities2-TrafficLightsEnhancement)" mod
5) includes correct settings for `version.dll` and `winhttp.dll` in `user.reg`


## Previous work
I previously created an initial guide on Reddit ( https://www.reddit.com/r/CitiesSkylines2/comments/197i518/running_cities_skylines_2_on_macbook_pro_m3_max/ )
This repository is a continuation of that work and should simplify the process for others.

