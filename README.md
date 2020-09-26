# ![tfsh-banner](Cover/tfsh-banner.png)

- [Tales from Skyrim's Holds](#)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
  - [How to start up Tales from Skyrim's Holds](#how-to-start-up-tales-from-skyrims-holds)
  - [Updating](#updating)
  - [In-Game MCM Options](#in-game-mcm-options)
    - [All Geared up Deriv](#all-geared-up-deriv)
    - [A Matter of Time](#a-matter-of-time)
    - [Dual Wield Parrying][#dual-wield-parrying]
    - [P.W.E.R.](#pwer)
    - [VioLens](#violens)
    - [Widget Mod](#widget-mod)
    - [XPMSSE (Preference)](#xpmsse-prefernece)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
    - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Preamble

This is a visual overhaul of Skyrim that tries to mimic the look of the "Tales of/from ..." Series, "The Wolf Among Us" and mainly "Borderlands" with their cell shaded visuals. The Visual Overhaul I used to create this list was stylized in a for my taste way to reflective way but I liked the textures themself so I have changed most of the normal maps of the textures i came around while testing this list. There are for sure textures missing that treatment but I will update this list everytime I update more of the normal maps to be less reflective.

For the gameplay this list contains mods that intend to make you stonger and feel like and actually special person in Skyrim just like the Vault Hunters and the Dragonborn should be able to feel in their stories.

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off when using and ENB, this list only uses ReShade which makes this step only necessary if you want to add an enb yourself.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.
Or use [Skyrim Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133) to clean everything.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Click on Install from Disk and select the .wabbajack file of this list.
~~(2. Click on Browse Modlists, and download Tales from Skyrim's Holds from the gallery.)~~
3. Once the download is done set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Tales from Skyrim's Holds`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Copy Game Folder Files

Copy the all of the files from the `Installation Folder/Game Folder Files` directory into your game folder.

## Mods to tweak to your taste

### Customizable UI Replacer

Customizable UI Replacer has multiple good looking presets.

- To test other presets just right-click the `Customizable UI Replacer` Mod and hit reinstall and select the preset you want.
- Once `Customizable UI Replacer` is reinstalled follow the steps for [A Matter of Time](#a-matter-of-time) and [Widget Mod](#widget-mod).

## How to start up Tales from Skyrim's Holds

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options

Once the game has loaded. Wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.
Mods or sections with (Preference) next to their name is solely preferential and do not affect the balance of the game.

### All Geared up Deriv

- Player (Preference)
  - Weapons - Player
    - Display Options
      - Shield stays on arm while Equipped: `Enabled`
  - Enable Misc Item Display: `Disabled`
- NPC:
  - Enable Weapons (Preference): `Enabled`
  - Enable Misc Item Display: `Disabled` (There's been numerous reports of NPCs crashing with this Enabled. Hence, it's recommended to be Disabled)

### A Matter of Time

- Presets:
  - Load user settings
  
### Dual Wield Parrying

- Block Key: `V` (set it to whatever suits you best.)

### P.W.E.R

- Settings
  - Followers enabled: `Enabled` (If you want your followers to be as powerful as you are.)

### VioLens

- Profile System
  - Load "TFSH-Profile"

### Widget Mod

- Maintainance
  - Load User Settings

### XPMSSE (Preference)

**Note:**
Xanza found that using these settings reduces save bloat by quite a bit.

- Styles:
  - Disable Style Cloak Spell: `Enabled`
  - Style Fitting Animations (All): `Disabled`
  - Style Fitting Dual Wield Animations (All): `Disabled`
  - Style Fitting Shield Animations (All): `Disabled`
  - Style Fitting Mixed Animations (All): `Disabled`

The rest can be set up however you like. I personally have Swords on back

## Other Post Installation FAQ

### Ultrawide Options

If you have an ultrawide monitor (21:9), the UI will be off. You will want to reinstall Dear Diary with the widescreen option. Pick any options on the FOMOD you want but ensure Extended UI, More Informative Console and Morehud is ticked.
You will also want to install the SkyHud - High Resolution Widescreen Fix from [here](https://www.nexusmods.com/skyrimspecialedition/mods/1778/?).

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
  - Under `[Render]`
    - Set Fullscreen to `True`
    - Set Borderless to `False`

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ReShade files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ReShade.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Xanza for writing most of this for his modlist.
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/EzioTheDeadPoet/Tales-from-Skyrims-Holds/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](https://github.com/EzioTheDeadPoet/Tales-from-Skyrims-Holds/blob/master/CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
