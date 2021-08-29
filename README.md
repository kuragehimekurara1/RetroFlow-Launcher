﻿
# RetroFlow-Launcher
[![](https://github.com/jimbob4000/HexFlow-Launcher/raw/main/Media/main_screen.png "main_screen")](https://github.com/jimbob4000/HexFlow-Launcher/blob/main/Media/main_screen.png)

# About
This is a modded version of HexFlow Launcher; a 3d coverflow like launcher for PS Vita.

This version includes categories for retro games which can be launched with RetroArch and DaedalusX64, without having to create bubbles for every game!

Display and launch your retro games and homebrews in style.  
**RetroFlow Launcher** features a 3d user interface to display your games with their box art and supports many customization options like custom covers and backgrounds.

Launching a game/app from **RetroFlow Launcher** will close the launcher automaticaly without asking.

### Supported systems:
PS Vita, PSP, Playstation, Nintendo 64, Super Nintendo, Nintendo Entertainment System, Game Boy Advance, Game Boy Color, Game Boy, Sega Mega Drive / Genesis, Sega Master System, Sega Game Gear.

[DaedalusX64](https://github.com/Rinnegatamante/DaedalusX64-vitaGL/releases) is required for N64 games. [RetroArch](https://www.retroarch.com/index.php?page=platforms) is required for other retro systems.




# Installation

#### 1. Install re-Patch reloaded 
Install the latest version of [re-Patch reloaded](https://github.com/SonicMastr/rePatch-reLoaded/releases) by SonicMastr.

Once installed, restart your Vita for the changes to take effect.

(This is plugin is used to avoid needing to create bubbles for each retro game).

#### 2. Install the RetroFlow VPK's.

Install the latest version of RetroFlow and two additional launcher VPK's from [here](https://github.com/jimbob4000/HexFlow-Launcher/releases).

RetroFlow is the app you will use to browse games
The other two VPK's are used to launch [RetroArch](https://www.retroarch.com/index.php?page=platforms) and [DaedalusX64](https://github.com/Rinnegatamante/DaedalusX64-vitaGL/releases).

#### 3. Add your retro games to RetroFlow

Launch RetroFlow for the first time, RetroFlow will create the folders where you can save your games.

Once it's finshed loading; close RetroFlow and copy your favourite retro games into the relevant subfolders below:

    ux0:/data/RetroFlow/ROMS/


#### 4. Download covers

To download cover art, press start, then choose which covers you would like to download. 


# RetroFlow FAQ's

#### Can I use HexFlow too?
Yes; RetroFlow is seperate, it uses different folders and a different title ID.

#### Do I need to create bubbles for retro games?
No; RetroFlow doesn't need bubbles for retro games provided you have installed re-Patch reloaded and the two DaedalusX64 and RetroArch launcher VPK's.

#### How should I name my games so covers are found?
It's recommended that your roms are named using the no-intro file naming convention, e.g. "Game Name (USA)" , these names are used to match with cover art.

#### How many games can I add?
Only add your favourite games.

RetroFlow isn't optimised for large collections of games, it's recommended that you only add you favourite retro games, adding too many games will result in longer load times.

#### Some systems aren't showing?
Empty collections are hidden by default, once you add some games into the roms folder, they will appear.

#### Can I change the Mega Drive name to Genesis?
Sure; changing your language to 'English - American' will change the 'Mega Drive' name and logo to 'Genesis'.

#### Can I change a core for RetroArch?
The cores have been set by system and cannot be changed on a game-by-game basis at the moment.

To change the core for an entire system, search for "Retroarch Cores" in the file below and edit accordingly.

    ux0:/app/RETROFLOW/index.lua


#### Can I change the rom folder locations?
The locations have been setup to keep things simple, if you would like to change the locations, search for "ROM Folders" in the file below and edit accordingly.

    ux0:/app/RETROFLOW/index.lua



## Adding PSP and Playstation games

These games require bubbles to be made in order to work.

For PSP or PS1 bubbles generated by Adrenaline Bubbles Manager you must set the value of **BubbleID** to **TitleID** in the settings menu of ABM tool.

For PSX2PSP, game folder name must match with the GameID. For example "ux0:pspemu/PSP/GAME/**SLES01234**".

**Subfolders and psp categories plugin are not supported**.

## Custom Covers

Place your custom covers in "_ux0:/data/HexFlow/COVERS/PSVITA/_"

Cover images must be in **png** format and file name must match the **App ID** or the **App Name** of each app (recomended resolution 256x256px). [Sample image](https://live.staticflickr.com/7176/6885249717_738e8ee187_n.jpg)

### Download Covers and Backgrounds

From v0.3 covers can be downloaded automatically from the settings menu (Start button). You can also download covers and backgrounds manually from the link below. A big thanks to **astuermer** for his contribution.

[https://github.com/andiweli/hexflow-covers](https://github.com/andiweli/hexflow-covers)

### Custom Background

Place your **Background.png** or **Background.jpg** image in "_ux0:/data/RetroFlow/_" (recomended resolution 1280x720px or less). Some custom backgrounds are available [HERE](https://github.com/andiweli/hexflow-covers/tree/main/Backgrounds)

### Custom Music

Place your **Music.mp3** file in "_ux0:data/RetroFlow/_" (music will play automaticaly when the "Sounds" option is enabled)

## AutoBoot

If you want to auto-launch **RetroFlow Launcher** every time your PS Vita boots up you can use the [**AutoBoot**](https://vitadb.rinnegatamante.it/#/info/261) plugin by Rinnegatamante.

## Controls

Navigate your library using the **DPad** or the **Left Stick** or with the **Touch Screen**.

**R/L triggers**: Skip 5 items

**Cross**: Select/Launch game/app

**Square**: Change Category

**Triangle**: Game Details

**Circle**: Change View/Cancel

**Start**: Settings menu



# Credits

Original [HexFlow](https://github.com/VitaHEX-Games/HexFlow-Launcher) app by : **VitaHex Games**

Programming/UI: **Sakis RG**

Developed with [Lua Player Plus](http://rinnegatamante.github.io/lpp-vita/) by **Rinnegatamante**


### Special Thanks

**Creckeryop**

**andiweli** ([HEXFlow Covers database](https://github.com/andiweli/hexflow-covers))

**DRok17** for his work on bubble builders.


### Translations

French - @chronoss

German - @stuermerandreas

Spanish - @kodyna91

Italian - @TheheroGAC

Russian - @_novff

Portuguese - @nighto

Japanese - @iGlitch


### Polite notice

Please note that I'm not a developer, this mod started as a personal project, please be mindful that there may be some redundant code, or some requests that will be beyond my knowledge to implement.
Please feel free to build upon the mod as long as you provide credit to the original HexFlow developer and the people who contributed to the project.


## Support

If you want to support VitaHex's work you can become a [Patron](https://www.patreon.com/vitahex).

PayPal option is also available [HERE](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RM8ECMVYMTXGJ&source=url)

[VitaHEX Twitter](https://twitter.com/VitaHex)

[VitaHEX Official Page](https://vitahex.weebly.com/)
