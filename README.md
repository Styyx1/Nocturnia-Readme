<!-- omit from toc -->
# Nocturnia

Wabbajack Modlist Installer for Skyrim Special Edition by Styyx  

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/AVO/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>    
<td><img src="https://cdn.discordapp.com/icons/997623524267139112/71c19848cc99c78d9f3c4854010ae065.webp?size=128" width="72px" /></td>
<td><a href="https://discord.gg/JycmyqzZz7">Support Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
***
<details>
<summary> <h1>Contents </summary>

- [Preamble](#preamble)
- [Mods to get familiar with:](#mods-to-get-familiar-with)
- [System Requirements](#system-requirements)
  - [1080p (my specs)](#1080p-my-specs)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
  - [Wabbajack Installation](#wabbajack-installation)
    - [Installing Wabbajack](#installing-wabbajack)
    - [Downloading and Installing Nocturnia](#downloading-and-installing-nocturnia)
      - [Problems with installation](#problems-with-installation)
- [Post-Installation](#post-installation)
  - [Game Folder](#game-folder)
- [Playing the List](#playing-the-list)
  - [Starting up the list](#starting-up-the-list)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Starting the Game](#starting-the-game)
- [Updating the modlist](#updating-the-modlist)
- [FAQ](#faq)
  - [Controller Setup](#controller-setup)
  - [Ultrawide Options](#ultrawide-options)
  - [Failed to create download folder](#failed-to-create-download-folder)
  - [Survival Mode](#survival-mode)
  - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [BethINI](#bethini)
  - [Zoomed in Display](#zoomed-in-display)
  - [Modifications](#modifications)
- [Removing the Modlist](#removing-the-modlist)
- [Known Issues](#known-issues)
- [I found a bug](#i-found-a-bug)
- [Changelog](#changelog)
- [Support](#support)
- [Credits and Thanks](#credits-and-thanks)
</details>

***

## Preamble

Nocturnia is a combat focused Requiem list fit for Requiem beginners. The focus of the list lies on enemy variety and exploration. There's not many new quests because the base game offers already more than I actually play. 
Some vanilla quests are overhauled and there is Darkend for you to explore as well.  
There are also some Requiem Addons. More on that below.

There's a ton of new enemies, some fitting better than others, and there's also some increased enemy density with interesting mechanics like enemies calling reinforments.

**Full modlist can be viewed [here](https://loadorderlibrary.com/lists/nocturnia)**
***
**What to expect from this list:**

- Introduction to Requiem
- focus on exploration
- increased enemy density
- ton of new enemy types
- survival mechanics, mostly focused on cold, optionally fully patched for hunger though

**What not to expect:**
- Next-Gen graphics (there are only little graphic mods and only for stuff I care about)
- Animation intense combat
- Vanilla/Vanilla+ gameplay
***

## Mods to get familiar with:
- [Requiem obviously](https://www.nexusmods.com/skyrimspecialedition/mods/60888)
- [Noxcrab Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/42591)
- [Minor Arcana](https://www.nexusmods.com/skyrimspecialedition/mods/61342)
- [Requiem - Magic Redone](https://www.nexusmods.com/skyrimspecialedition/mods/59302)
- [Small Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/42633)
 
***
Some mods/mechanics are customised by me, check out [a short summary](/files/CustomChanges.md) of some of them.

***
[![Requiem Starter Guide](https://img.youtube.com/vi/fG7D8meR0cY/hqdefault.jpg)](https://youtu.be/fG7D8meR0cY)

***
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].
***
## System Requirements

Nocturnia is aimed at fairly low tier machines but here's my system:

### 1080p (my specs)
- CPU: AMD Ryzen 7 3700X
- RAM: 16GB DDR4
- Drive: SSD
- GPU: NVIDIA GeForce RTX 3070 8GB

I play the list with 60 fps locked and only slightly go below that in Morthal.
It should run fine on lower specs as well, but I recommend at least 6GB VRAM (GPU).

**I can only answer performance questions about my specs as I don't have different systems flying around to check!**

Space required: 
- Approx 140GB (Downloads included, ~90GB without downloads) + 20-30GB space for temp files. I tried to keep the size small, but that's the best I could do for now.
- **You can safely delete the downloads after the list is installed**
 
Size without downloads and space for temp files: 
- Approx 90GB
***
## Installation

Installing Nocturnia is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).
***
### Pre-Installation

Prior to installing Nocturnia, please complete the following steps.
>**If you already installed ANY Skyrim Special Edition modlist with Wabbajack before, none of the Pre-Installation steps are needed anymore**


1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside /Documents/My Games/.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like C:\Games is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.


> **Step 3 and 4 are only necessary if you modded the game without 'stock game' and cleaned the master files**
***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Nocturnia

Downloading and installing Nocturnia can take a while depending on your internet connection and computer. To install Nocturnia, complete the following steps.

1. Open Wabbajack and click on ``browse modlists``
2. Press the download button on Nocturnia and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Nocturnia. **Do not install it to your desktop, downloads folder or Skyrim's game folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster. You can also have a shared download folder across all Wabbajack lists on a different drive than the install drive.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

- Files beginning with ``Data_`` fail to download:
    - these are the game's files. the list is compiled with version 1.6.1170, if it updated since then, this is why you have that error. Either wait for me to update the list or downgrade your game via steam console (you will find tons of tutorials for how to do that online, use google)


## Post-Installation

### Game Folder

Nocturnia uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called ``Stock Game``. 

***
## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Play Nocturnia` and press the run button.

***

### In-Game MCM Options

Almost all of the MCM options are automatically configured for you already. Wait until all notifications on the top left are gone before opening the MCM. 
**Failing to do so will cause quite a few issues later on and will require you to start a new save.** 

Note that all keybinding are set to my liking for a **Gamepad**. I do not know the keyboard and mouse settings as I don't use it for playing. 

You can tweak the MCMs to your liking, just use common sense and don't complain if the settings you changed break stuff because there may or may not be a reason I picked certain options by default.

***

### Starting the Game
After starting the game you are asked if you want to skip the intro. For the love of whoever, please click `yes` as I did not test the vanilla intro and won't fix any issues it comes with.
You can then create your character as you wish. After finishing your character, MCM recorder starts automatically, wait for it to finish before you proceed. 
**INFO:** if you are prompted with an error and are asked to try again or skip, just select skip, that is usually because i forgot to remove a recording of a MCM that doesn't exist anymore. No big deal, nothing bad will happen.
***
## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### Failed download for Rare Curios
Bethesda uploaded different files to their ingame store and steam. If you fail, delete the files ``bgssse037-curios.bsa`` and ``bgssse037-curios.esl`` and download them from the ingame mod store via starting the game from steam.

### Controller Setup

Refer to the [Gamepad Keybind page](files/Gamepad-Keybinds.md) for any questions related to playing with a controller. 
***
### Ultrawide Options

I personally do not own an Ultrawide, so I cannot offer support. I added some widescreen variants of the mods in MO2, but I can't test them.  
Filter for ``Widescreen`` at the bottom of MO2 and activate the unticked mods. I don't know if that's all you need, but that's all I can help with.

***
### Failed to create download folder

Upon opening MO2 you may get a error warning like this: ``“Failed to create G:/Modlist Downloads/Traveler your user account probably lacks permission”``. This is due to Wabbajack not changing the ini file of MO2. To fix this find the file ``ModOrganizer.ini`` inside the same folder as the MO2 exe is and change the line:``download_directory=G:/Modlist Downloads/Traveler`` to ``download_directory=Your Prefered Download Folder``. It's best to find the line inside the ini by using ``crtl + f``.
***
### Survival Mode

While the list is made with Survival enabled by default (with disabled hunger and exhaustion, so effectively only cold), you can disable it in the settings menu whenever you want (just give it a few seconds to take effect) and don't rapid fire switch between Survival and non-Survival.
***
### My damage is not consistent

That's intended, it's my personal gameplay tweaks and damage ranges are set to **`15%`**, this includes hostile spells.
***
### Follower X won't follow me:
Probably intended, this is not the vanilla game
***
### I can't become the head of every guild:
Intended, you can only finish one of the major guild quest lines
***
### I can't open the map and don't see a compass
Intended, check out [Navigation Restrictions](https://www.nexusmods.com/skyrimspecialedition/mods/129086) \
**INFO:** there are a map and a compass in the starting choices menu right after you created your character.
***
### I don't see quest markers:
Intended, I hate quest markers since they ruin the game imo and make it so you only run brainlessly from marker to marker.
You can enable them by disabling `Nocturnia No Markers` in MO2
***
### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI. You find BethINI inside the tools folder within the list installation folder.

- `Shadow Resolution`: 2048
- `Remove Shadows`: I really don’t recommend turning this on, but if you must then you can.

### Zoomed in Display

This is caused by Windows display scaling feature. To fix this you can do either of the following.
- Set display scaling back to 100% in Windows screen resolution settings.
- Edit SSE Display Tweaks ini file under Render
	- Fullscreen: `True`
	- Borderless: `False`

***
    
### Modifications
**Can I add? Is X compatible?**

- Yes you can if you know what you are doing. 
- Yes it is compatible when you know what you are doing.
- No simply downloading a mod and activating it in MO2 is not knowing what you're doing.
***
## Removing the Modlist

Simply delete the folder and you have uninstalled it.

## Known Issues

[check](https://github.com/Styyx1/Nocturnia-Readme/blob/master/Known%20Issues.md)

## I found a bug
report the bug [here](https://github.com/Styyx1/Nocturnia-Readme/issues/new?assignees=Styyx1&labels=bug&projects=&template=bug-report.md&title=%5BBUG%5D)

## Changelog

To see what changes happened in each version, please refer to the [Changelog.](/Changelog.md) Please note that after a major version update (x.0.0), the changelog might not cover every change.

## Support

If you feel like I did a good job with the list and want to support my work, consider donating to my [ko-fi](https://ko-fi.com/styxus). 


## Credits and Thanks

- _YOU_ for reading this.
- Althro for assisting with so many things. You’re awesome.
- Spaniard for being an invaluable source of knowledge and helping me a lot with the mod choices.
- Destiny for proofreading the readme and pointing out many errors. Also for testing the list and giving helpful suggestion to improve it.
- Sr. Kaio for testing the list and helping me find issues.
- Abandoned by Arkay for helping me with Requiem and the addon choices.
- Zélie for ideas to work without the DLC
- The Animonculory Dev Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.
