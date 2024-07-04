# Tales from the Northern Lands

![tfsh-banner](Cover/tfsh-banner.webp)

![status](https://img.shields.io/badge/dynamic/json?label=Status&query=Status&url=https%3A%2F%2Fraw.githubusercontent.com%2Fwabbajack-tools%2Fmod-lists%2Fmaster%2Freports%2FLuca%2FTalesFromTheNorthernLands%2Fstatus.json&style=for-the-badge)
![version](https://img.shields.io/badge/dynamic/json?label=version&query=%24%5B%3F%28%40.links.machineURL%3D%3D%22TalesFromTheNorthernLands%22%29%5D.version&url=https%3A%2F%2Fraw.githubusercontent.com%2FEzioTheDeadPoet%2FTales-from-the-Northern-Lands%2Fmaster%2Fwabbajack_ui.json&style=for-the-badge)
[![Discord](https://img.shields.io/discord/1132691434420576337?style=for-the-badge&label=Aetherius%20Modding)](https://discord.gg/aetherius-modding)

**Development on this project is paused indefinitely. IF it ever returns it will be completely different.**

## Table of Contents

1. [Tales from the Northern Lands](#tales-from-the-northern-lands)
   1. [Table of Contents](#table-of-contents)
   2. [Preamble](#preamble)
   3. [Modlist](#modlist)
   4. [Screenshots](#screenshots)
   5. [Installation](#installation)
      1. [Required Accounts](#required-accounts)
      2. [Pre-Installation](#pre-installation)
         1. [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
         2. [Installing .NET 5.0](#installing-net-50)
      3. [Steam Config](#steam-config)
            1. [Game Location](#game-location)
            2. [Disable the Steam Overlay](#disable-the-steam-overlay)
            3. [Change Steams Update Behavior](#change-steams-update-behavior)
            4. [Set the Game language to English](#set-the-game-language-to-english)
         1. [Clean Skyrim](#clean-skyrim)
         2. [Start Skyrim](#start-skyrim)
      4. [Using Wabbajack](#using-wabbajack)
         1. [Preparations](#preparations)
         2. [Downloading and Installing](#downloading-and-installing)
            1. [Manual Downloads](#manual-downloads)
            2. [Problems with Wabbajack](#problems-with-wabbajack)
               1. [Could not download x](#could-not-download-x)
               2. [x is not a whitelisted download](#x-is-not-a-whitelisted-download)
               3. [Wabbajack could not find my game folder](#wabbajack-could-not-find-my-game-folder)
               4. [Windows is reporting that a virus has been detected](#windows-is-reporting-that-a-virus-has-been-detected)
   6. [How to Launch Tales from the Northern Lands](#how-to-launch-tales-from-the-northern-lands)
   7. [Updating](#updating)
   8. [Controls](#controls)
   9. [In-Game MCM Options](#in-game-mcm-options)
   10. [Other Post Installation FAQ](#other-post-installation-faq)
       1. [Ultrawide Options](#ultrawide-options)
       2. [Tweaking the Game Settings](#tweaking-the-game-settings)
          1. [Using the pre-configured ModOrganizer Profiles](#using-the-pre-configured-modorganizer-profiles)
          2. [BethINI Method](#bethini-method)
       3. [Zoomed in Display](#zoomed-in-display)
       4. [Removing the Modlist](#removing-the-modlist)
   11. [Credits and Thanks](#credits-and-thanks)
   12. [Contact](#contact)
   13. [Contributing](#contributing)
   14. [Changelog](#changelog)
   15. [Licenses](#licenses)

## Preamble

This is a visual and gameplay overhaul focused on running on old and new systems alike.
I myself use a GTX 950 2GB VRAM, a Ryzen 5 2400G, 24GB RAM, have the game installed on an SSD and get 48-78 FPS in the Performance Profile, 34-60 FPS in the Balanced Profile(I will play with this most of the time) and 15-28 FPS with the Default Profile (the one without an extra profile name). *All those FPS vales are with the ReShade on, if you turn it off ([see Controls](#controls)) you can gain between 5-15 FPS depending on the region and the weather.*

For the **visual overhaul** I tried to mimic the look of the "Tales of/from ..." Series, "The Wolf Among Us" and mainly "Borderlands" with their cell-shaded visuals. The visual overhaul I initially used to create this list [Artistic Skyrim Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/9111), was stylized in a for my taste way to reflective way but I liked the textures themself, so I have changed most of the normal maps of the textures I came around while testing this list. And thanks to NotSandwich on the Wabbajack Discord there are no reflecting textures anymore, due to an INI tweak he recommended. Now I am still using it as a baseline but moved on to using the still actively updating and expanding [Borderlands Style Overhaul by Kanjs](https://www.nexusmods.com/skyrimspecialedition/mods/58407), but without the ENB and my ReShade preset instead.

For the **gameplay** this list merges gameplay-changing mods mixed and chosen from different overhaul projects like the SimonRim or SkyRem mods. It also features an incredible amount of weapon-variations (different enchantments on similar weapons) and wearable-variations (again different enchantments on the same item) thanks to [Halgari's RPG Loot Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/37736) in its new form found [here](https://github.com/Synthesis-Collective/HalgarisConsistentRPGLoot) and a new inventory overhaul created by me specifically for this list powered by [Noggog's Synthesis Tool](https://github.com/Noggog/Synthesis).

If you need a perfectly balanced list this 9999% isn't for you, I make sure that things work and that there are no big obvious exploits. I tried not to break the balance too much when I overhauled the way the inventory system worked, so I had to write code into the overhaul patcher to adjust the magic effects that affect those systems to keep it in line with my changes. But I won't micromanage Leveled Lists or nerf some of the crazy enchantments the generator will provide for this list. The end goal of this list is to be fun and not a challenge or torture. *(I removed only 2 enchantment types, bound weapon giving enchantments that had the risk of crashing the game when in NPC inventories, and press "wait" to get infinite money enchantments. Those are game-breaking issues in the literal and figurative way.)*

I used my other list [SME(FT) - Skyrim Modding Essentials (Fixes & Tools)](https://eziothedeadpoet.github.io/SME-FT-/) as a baseline to create this. If you are interested in building your own setup or want a vanilla list just with fixes to test your mods feel free to try it out. (I am not as actively updating it anymore.)

## Modlist

The list of mods can be found on [LoadorderLibrary](https://loadorderlibrary.com/lists/tales-from-the-northern-lands).

## Screenshots

So I have created a page where you can share your screenshots of this list with others and I hope you can help me out or have fun sharing screenshots since I am not the best at taking nice-looking screenshots myself.
You can make screenshots using the `F11` key and find them in the `Screenshots` folder inside of the `Screenshots ! Racemenu Presets ! Game Generated` Mod.
I have moved all screenshots to this [page](SCREENSHOTSDISPLAY.md) to never be limited by the space on this overview and instructions page.
To learn how to share your screenshots check the [Contibutng](#contiuting) section of this guide.

## Installation

### Required Accounts

| Website |Comment | Mandatory |
|-|-|-|
| [Nexus Mods](https://users.nexusmods.com/register) | Premium highly recommended for automated and faster downloads. | Yes |
| [MEGA](https://mega.nz/register/aff=SarImJUJMEM) | Works without an account as well but logged in uses have slightly higher download bandwidth per day. | No |

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019".

|[Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe)|

#### Installing .NET 5.0

This is a needed dependency for mods used with this list.
So please make sure to install it to avoid any issues. Download the desktop app x64 AND the console app x64 versions from [Microsoft](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).

[Direct Link Desktop](https://download.visualstudio.microsoft.com/download/pr/1daf85dc-291b-4bb8-812e-a0df5cdb6701/85455a4a851347de26e2901e043b81e1/windowsdesktop-runtime-5.0.12-win-x64.exe) | [Direct Link Console](https://download.visualstudio.microsoft.com/download/pr/28b0479a-2ca7-4441-97f2-64a3d64b2ea4/9995401dac4787a2d1104c73c4356f4d/dotnet-runtime-5.0.12-win-x64.exe)

### Steam Config

##### Game Location

Make sure your game is **NOT** installed in a _common folder_ like your `Desktop`, `Downloads` or `Program Files` folder (like the default steam location). If you only have one drive and can't create a second steam library with steam use LostDragonist's [steam-library-setup-tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to create a second one on your main drive. When you have a new steam library setup move your game there **using the steam feature** to do so.

*Creating a new library with Steam:*

![SteamLibrarySetup_1](readme_assets/images/SteamLibrarySettings_1.webp)
![SteamLibrarySetup_2](readme_assets/images/SteamLibrarySettings_2.webp)

*Moving the Game:*

![SteamMOveGame_1](readme_assets/images/SteamMoveGame_1.webp)
![SteamMoveGame_2](readme_assets/images/SteamMoveGame_2.webp)

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off when using and ENB, this list only uses ReShade which makes this step only necessary if you want to add an ENB yourself.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab, and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

##### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

![SteamSettings_1](readme_assets/images/SteamSettings_1.webp)
![SteamSettings_2](readme_assets/images/SteamSettings_2.webp)

##### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I can not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.
But verifying your installation via steam should be enough, if the installation fails follow the steps above.

How to verify Skyrim Special Edition with Steam:

- Open your Steam Library tab
- Right-click Skyrim Special Edition
- Select Properties
- Select Local Files
- Select Verify Integrity of Local Files

#### Start Skyrim

After you have done everything above and got a clean Skyrim Special Edition installation, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace these graphics settings.
Start the game and exit once you're on the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://www.wabbajack.org/#/) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your `Desktop`, `Downloads` or `Program Files` folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will detect the optimal amount of threads at the beginning of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Select a folder for all the mods that need to be downloaded somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Tales from the Northern Lands/downloads` or `Modlists/Downloads`).
2. Download all the mods [here](#manual-downloads) manually and put them in the folder created in step 1 (The reason for this is, that mods hosted on mega are prone to cause issues when installing and compiling modlists, and the manual download step for them during the installation sometimes doesn't work or some files are just too big so they are likely to fail because of that and I had better chances of success downloading those files manually.).
3. Open Wabbajack
4. Click on the settings icon and log in with your Nexus Mods and Vector Plexus Account. (Optionally MEGA as well.)
5. Click on `Browse Modlists`, and download Tales from the Northern Lands from the gallery.)
6. Once the download is done set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Tales from the Northern Lands`). The downloads path should be the one you created in step 1.
7. Click the Go/Begin button
8. Wait for Wabbajack to finish
[Post-Installation](#how-to-launch-tales-from-the-northern-lands)

##### Manual Downloads

It is absolutely required to manually download the files coming from MEGA, but the Nexus Mods files are only linked here, because they are likely to cause issues because of their size. The Vector Plexus File is listed for those that can't login to VP due their account being created with a social login.

| Host       | Mod                                    | Author                                                                           | Website                                                              | Download                                                                                              |
|------------|----------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| MEGA       | Smooth Jump Stagger Animation          | [Smooth aka Skypia](https://www.nexusmods.com/skyrimspecialedition/users/433905) | [Website](https://smooths.tistory.com/23)                            | [Direct Download](https://mega.nz/file/5PxWBQga#jGc-JE1u8_QiZPnWNLIXvXKRNWgp1oTW3sgqTHY5eV8)          |
| MEGA       | Extra Drawing Nemesis Free SE          | [Smooth aka Skypia](https://www.nexusmods.com/skyrimspecialedition/users/433905) | [Website](https://smooths.tistory.com/44)                            | [Direct Download](https://mega.nz/file/YKZAGDqZ#f2U6xmdd6mNFvN1XFQOYSxQpIbztDWWGYNfOf9jEpxk)          |
| MEGA       | Smooth Combat Animation by Skill Level | [Smooth aka Skypia](https://www.nexusmods.com/skyrimspecialedition/users/433905) | [Website](https://smooths.tistory.com/18)                            | [Direct Download](https://mega.nz/file/4TJVGKjb#fLIBqEXkiV0g5SPuPtyrxqTi-HUai-S80sxOqj9r19w)          |
| Nexus Mods | Cleaned Skyrim SE Textures             | [Kartoffel](https://www.nexusmods.com/skyrimspecialedition/users/6129887)        | [Website](https://www.nexusmods.com/skyrimspecialedition/mods/38775) | [Direct Download](https://www.nexusmods.com/skyrimspecialedition/mods/38775?tab=files&file_id=248251) |
| Nexus Mods | Unofficial High Definition Audio Project | [sharrken](https://www.nexusmods.com/skyrimspecialedition/users/4158519) | [Website](https://www.nexusmods.com/skyrimspecialedition/mods/18115) | [Direct Download Voices EN Part 1](https://www.nexusmods.com/skyrimspecialedition/mods/18115?tab=files&file_id=57972) + [Direct Download Voices EN Part 2](https://www.nexusmods.com/skyrimspecialedition/mods/18115?tab=files&file_id=57857) |
| Nexus Mods | Kanjs - Borderlands Style Anniversary Edition Mega Pack | [Kanjs](https://www.nexusmods.com/skyrimspecialedition/users/4685594) | [Website](https://www.nexusmods.com/skyrimspecialedition/mods/60023) | [Direct Download](https://www.nexusmods.com/skyrimspecialedition/mods/60023?tab=files&file_id=248844) |
| Vector Plexus | High Poly Head | KouLeifoh | [Website](https://vectorplexus.com/files/file/283-high-poly-head/) | You need to get `High_Poly_Head_v1.4_(SE).zip`|

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

###### Could not download x

If a mod got updated and the old files got deleted, it is impossible to download them. In this case, just wait till I update the modlist.

###### x is not a whitelisted download

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

###### Wabbajack could not find my game folder

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step. If you own the game make sure you did [start Skyrim once](#start-skyrim).

###### Windows is reporting that a virus has been detected

Windows 10 has started to auto-quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected. This is a known false positive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. An example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## How to Launch Tales from the Northern Lands

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button. Under the run button, you can find a shortcut menu that allows you to make a desktop shortcut.


*If the game doesn't launch correctly check [this](#windows-is-reporting-that-a-virus-has-been-detected) and the [pre-installation steps](#pre-installation) as those are the solution for the most common issues besides an failed installation.*


![launch](readme_assets/images/Launch_MO2.webp)

![run](readme_assets/images/ModOrganizer_run.webp)

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the modlist when updating!**

Additionally installed mods will be removed.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button. Make sure to do backups of your saves in case anything goes wrong.

## Controls

![ControlLayout](readme_assets/images/ControlLayout.webp)

[click here to create your cheat-sheet, if you plan to change them.](http://www.keyboard-layout-editor.com/##@_backcolor=%231C2229&name=Tales%20From%20The%20Northernlands%20Keybinds&author=Luca%7CEzioTheDeadPoet&notes=Built%20on%20Dylan%20Perry's%20Layout%20for%20Ultimate%20Skyrim.%3B&@_c=%23f9a7a7&fa@:0&:0&:0&:0&:0&:0&:0&:0&:0&:0&:2%3B%3B&=Esc%0A%0A%0A%0A%0A%0A%0A%0A%0A%0APause&_x:1&c=%238dc4d6%3B&=F1%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AGroup%20Equip%201&=F2%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AGroup%20Equip%202&=F3%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AGroup%20Equip%203&=F4%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AGroup%20Equip%204&_x:0.5&c=%23f9a7a7&f2:2%3B&=F5%0AQuick-save&_c=%23a1a1a1%3B&=F6&=F7&=F8&_x:0.5&c=%23f9a7a7%3B&=F9%0AQuick-load&_c=%235c9dff&f2:1%3B&=F10%0AShow%20Key-binds&_c=%23f9a7a7%3B&=F11%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AScreen-shot&=F12%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AScreen-shot%20(Steam)&_x:0.25&c=%23a1a1a1%3B&=PrtSc&=Scroll&=Pause%3B&@_y:0.5&c=%23f9a7a7&fa@:0&:1&:1&:1&:1&:1&:1&:1&:1&:1&:2%3B%3B&=~%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ADev%20Console&=1%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%201&=2%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%202&=3%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%203&=4%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%204&=5%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%205&=6%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%206&=7%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%207&=8%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHotkey%208&_c=%23a1a1a1%3B&=9&=0&=-&=%2F=&_w:2%3B&=Backspace&_x:0.25%3B&=Insert&_c=%238dc4d6%3B&=Home%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AReshade%20Menu&_c=%23a1a1a1%3B&=PgUp&_x:0.25%3B&=Num%20Lock&=%2F%2F&=*&=-%3B&@_c=%23f9a7a7&w:1.5%3B&=Tab%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ATween%20Menu&=Q%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AFavs%20Menu&=W%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AMove%20Forward&=E%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ATalk%20%2F%2F%20Activate&=R%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AReady%20%2F%2F%20Sheathe&_c=%23cda1ff%3B&=T%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AUse%20H%20Potion&=Y%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AUse%20S%20Potion&_c=%23a1a1a1%3B&=U&_c=%23f9a7a7%3B&=I%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AInventry%20Menu&=O%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AMagic%20Menu&=P%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AStats%20Menu&_c=%23a1a1a1%3B&=%5B&=%5D&_w:1.5%3B&=%5C&_x:0.25%3B&=Delete&_c=%238dc4d6%3B&=End%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AToggle%20Reshade&_c=%23a1a1a1%3B&=PgDn&_x:0.25%3B&=7&=8&=9&_h:2%3B&=+%3B&@_c=%23f9a7a7&w:1.75%3B&=Caps%20Lock%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AToggle%20Walk&=A%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AMove%20Left&=S%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AMove%20Back&=D%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AMove%20Right&=F%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AShout%20%2F%2F%20Power&_c=%23cda1ff%3B&=G%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AUse%20M%20Potion&_c=%2390d685%3B&=H%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AHorse%20Whistle&_c=%23f9a7a7%3B&=J%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AQuests%20Menu&=K%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AWait&_f2:1%3B&=L%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ACustom-Skill%20Menus&_c=%23a1a1a1%3B&=%2F%3B&='&_w:2.25%3B&=Enter&_x:3.5%3B&=4&=5&=6%3B&@_c=%23f9a7a7&fa@:0&:1&:1&:1&:1&:1&:1&:1&:1&:1&:2%3B&w:2.25%3B&=Shift%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ASprint&=Z%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ASwitch%20View&=X%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AAuto-Move&=C%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ASneak&_c=%23f781c1&f2:1%3B&=V%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ABlocking%20(Dual-wielding)&_c=%23ccc404&fa@:0&:1&:1&:1&:1&:1&:1&:1&:1&:1&:2%3B%3B&=B%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AToggle%20Nighteye&=N%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ABeast-vision&_c=%23f9a7a7%3B&=M%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AMap&_c=%238dc4d6&f2:1%3B&=%3C%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AToggle%20Zoom%20MiniMap&_fa@:0&:1&:1&:1&:1&:1&:1&:1&:1&:1&:2%3B%3B&=%3E%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AToggle%20MiniMap&=%3F%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AToggle%20HUD&_c=%23a1a1a1&w:2.75%3B&=Shift&_x:1.25%3B&=%E2%86%91&_x:1.25%3B&=1&=2&=3&_h:2%3B&=Enter%3B&@_c=%238dc4d6&w:1.25%3B&=Ctrl%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ASwap%20Side%20(Camera)&_c=%23a1a1a1&w:1.25%3B&=Win&_c=%238dc4d6&w:1.25%3B&=Left%20Alt%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ALock%20On%20(Camera)&_c=%23f9a7a7&w:6.25%3B&=Space%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AJump&_c=%23a1a1a1&w:1.25%3B&=Right%20Alt&_w:1.25%3B&=Win&_w:1.25%3B&=Menu&_w:1.25%3B&=Ctrl&_x:0.25%3B&=%E2%86%90&=%E2%86%93&=%E2%86%92&_x:0.25&w:2%3B&=0&=.%3B&@_y:0.25&c=%23f9a7a7%3B&=M1%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ARight%20Hand&=M2%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ALeft%20Hand&_fa@:2&:1&:1&:1&:1&:1&:1&:1&:1&:1&:2%3B&w:2%3B&=Wheel%20(Scroll)%0A%0A%0A%0A%0A%0A%0A%0A%0A%0AZoom%20Camera&_c=%238dc4d6&w:2%3B&=Wheel%20Up%2F%2FDown%0A%0A%0A%0A%0A%0A%0A%0A%0A%0ASwitch%20Targets%20(Camera)%20(Lock%20on))

## In-Game MCM Options

Pre-configured.

## Other Post Installation FAQ

### Ultrawide Options

Enable the mods in the `21x9 Patches` category in ModOrganizer.
**I can't and won't guarantee that any widescreen resolution will work flawlessly. And want to stress that the intended way of play is standard widescreen 16:9.**

### Tweaking the Game Settings

#### Using the pre-configured ModOrganizer Profiles

To use my pre-configured settings you can select the different profiles in ModOrganizer. **Just keep in mind that your saves are tied to their profile.**

1. Profile Quick-select.
2. Profile Menu.
   - It has options to transfer your saves.

![ModOrganizerSelectProfile](readme_assets/images/ModOrganizerSelectProfile.webp)

#### BethINI Method

*Settings tweaked this way will be reverted after updates.*

- To change the quality settings:
  - Locate the `BethINI.exe` in `...\\(name of the MO 2 folder(the installation path you choose for the modlist))\tools\BethINI (ONLY LAUNCH WITH MO AND THE GAME CLOSED)` and run it with the game and MO2 closed.
    - In there (BethINI) go to the `Setup` tab and point BethINI to your `ModOrganizer.EXE`. (The place the list is installed in.)
    - Select the Profile you intend to use in the INI Path section (Either the Normal one or the `Basics` one).
    - Select a Preset fitting your Hardware.
    - Save and Exit

I recommend tweaking the `Detail` section for more FPS(If nothing else worked):

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage-looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off (if you decided to use one). Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
  - Under `[Render]`
    - Set Fullscreen to `True`
    - Set Borderless to `False`

### Removing the Modlist

You can just remove the MO2 folder and be done with it.

## Credits and Thanks

- YOU for reading the readme. Thanks a ton!!
- Xanza for writing A LOT of this for his modlist.
- ForgottenGlory for making SME(FT) and this modlist possible due to his early support. 🧡
- Thanks to NotSandwich on the Wabbajack Discord for sharing some awesome .ini edits that killed all unwanted reflections.🥪
- Everyone who was giving me feedback on the artistic choices.
- the creator of ReShade with its generous [License](ReShade/RESHADELICENSE.md#reshade-license) that allows me to include it.
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone on the WJ Team
- Noggog and Halgari for making the large variety in weapons and Armor possible, by making the Mutagen Framework and the 1st iteration of the RPG Loot patcher respectively.
- The team behind the Artistic Skyrim Overhaul for inspiring me to make this because of its very distinctive unique style.
- Kanjs for reviving the spirit of art-driven Skyrim Texture Overhauls.
- Nem aka. Eggy aka. Osmosis-Wrench and JanuarySnow for both helping me make some custom edits to a few mods used in this list.
- ALL the mod authors that made the mods featured in this list.
- Special thanks to all the other people listed [here](https://eziothedeadpoet.github.io/AboutMe/HALLOFFAME.html) that support(ed) this and other projects of mine.

## Contact

While I'm nearly always available on the [Aetherius Modding Discord](https://discord.gg/aetherius-modding), I would advise checking previous threads in the dedicated forum channel for this list on the discord server first if you have any problems.

**I WILL NOT PROVIDE SUPPORT FOR YOU IN DMs.**

**DO NOT CONTACT MOD-AUTHORS WITH ISSUES!!**

## Contributing

See [How to contribute](HOWTOCONTRIBUTE.md).

## Changelog

See [Changelog](CHANGELOG.md).

## Licenses

- [ReShade License](ReShade/RESHADELICENSE.md)

---
