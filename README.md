# Tales from the Northern Lands

![tfsh-banner](Cover/tfsh-banner.webp)

![status](https://img.shields.io/endpoint?url=https://build.wabbajack.org/lists/status/TalesFromTheNorthernLands/badge.json)

## Index

<!-- markdownlint-disable MD033 -->

<a href="#tales-from-the-northern-lands">Tales from the Northern Lands</a>
<ul>
  <li><a href="#preamble">Preamble</a></li>
  <li><a href="#screenshots">Screenshots</a></li>
  <li><details><summary><a href="#installation">Installation</a></summary>
    <ul>
      <li><details><summary><a href="#pre-installation">Pre-Installation</a></summary>
        <ul>
          <li><ahref="#installing-microsoft-visual-c-redistributable-package">Installing Microsoft Visual C++ Redistributable Package</a></li>
          <li><a href="#steam-config">Steam Config</a>
            <ul>
              <li><a href="#disable-the-steam-overlay">Disable the Steam Overlay</a><li>
              <li><a href="#change-steams-update-behavior">Change Steams Update Behavior</a></li>
              <li><a href="#set-the-game-language-to-english">Set the Game language to English</a></li>
            </ul>
          </li>
          <li><a href="#clean-skyrim">Clean Skyrim</a></li>
          <li><a href="#start-skyrim">Start Skyrim</a></li>
        </ul>
      </details></li>
      <li><details><summary><a href="#using-wabbajack">Using Wabbajack</a></summary>
        <ul>
          <li><a href="#preparations">Preparations</a></li>
          <li><a href="#downloading-and-installing">Downloading and Installing</a>
            <ul>
              <li><a href="#problems-with-wabbajack">Problems with Wabbajack</a></li>
            </ul>
          </li>
        </ul>
      </details></li>
    </ul>
  </li>
  <li><a href="#how-to-start-up-tales-from-the-northern-lands">How to start up Tales from the Northern Lands</a></li>
  <li><a href="#updating">Updating</a></li>
  <li><a href="#in-game-mcm-options">In-Game MCM Options</a></li>
  <li><a href="#controls">Controls</a></li>
  <li><details><summary><a href="#other-post-installation-faq">Other Post Installation FAQ</a></summary>
    <ul>
      <li><a href="#ultrawide-options">Ultrawide Options</a></li>
      <li><a href="#smoothcam-note">SmoothCam Note</a></li>
      <li><a href="#tweaking-the-game-settings">Tweaking the Game Settings</a></li>
      <li><a href="#zoomed-in-display">Zoomed in Display</a></li>
      <li><a href="#removing-the-modlist">Removing the Modlist</a></li>
    </ul>
  </details></li>
  <li><a href="#credits-and-thanks">Credits and Thanks</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#changelog">Changelog</a></li>
  <li><a href="#licenses">Licenses</a></li>
</ul>
<!-- markdownlint-enable MD033 -->

## Preamble

This is a visual and gameplay overhaul focused on running on old and new systems alike.
I myself use a GTX 950 2GB VRAM, a Ryzen 5 2400G, 24GB RAM, have the game installed on an SSD and get 48-78 FPS in the Performance Profile, 34-60 FPS in the Balanced Profile(I will play with this most of the time) and 15-28 FPS with the Default Profile (the one without an extra profile name). *All those FPS vales are with the ReShade on, if you turn it off ([see Controls](#controls)) you can gain between 5-15 FPS depending on the region and the weather.*

For the **visual overhaul** I tried to mimic the look of the "Tales of/from ..." Series, "The Wolf Among Us" and mainly "Borderlands" with their cell-shaded visuals. The visual overhaul I initially used to create this list [Artistic Skyrim Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/9111), was stylized in a for my taste way to reflective way but I liked the textures themself, so I have changed most of the normal maps of the textures I came around while testing this list. And thanks to NotSandwich on the WJ discord there are no reflecting textures anymore, due to an INI tweak he recommended. Now I am still using it as a baseline but moved on to using the still actively updating and expanding [Borderlands Style Overhaul by Kanjs](https://www.nexusmods.com/skyrimspecialedition/mods/58407), but without the ENB and my ReShade preset instead.

For the **gameplay** this list merges a number of gameplay changing mods mixed and chosen from different overhaul projects like the SimonRim or SkyRem mods. It also features an incredible amount of weapon-variations (different enchantments on similar weapons) and wearable-variations (again different enchantments on the same item) thanks to [Halgari's RPG Loot Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/37736) and a new inventory overhaul created by me specifically for this list powered by [Noggog's Synthesis Tool](https://github.com/Noggog/Synthesis).
If you need a perfectly balanced list this 9999% isn't for you.

I used my other list [SME(FT) - Skyrim Modding Essentials (Fixes & Tools)](https://eziothedeadpoet.github.io/SME-FT-/) as a baseline to create this. If you are interested in building your own setup or want a vanilla list just with fixes to test your own mods feel free to try it out. (I am no longer active)

## Screenshots

So I have created a page where you can share your screenshots of this list with others and I really hope you can help me out or have fun sharing screenshots since I am not the best at taking nice-looking screenshots myself.
You can make screenshots using the `F11` key and find them in the `Screenshots` folder inside of the `Screenshots ! Racemenu Presets ! Game Generated` Mod.
I have moved all screenshots to this [page](SCREENSHOTSDISPLAY.md) to never be limited by the space on this overview and instructions page.
To learn how to share your screenshots check the [Contibutng](#contiuting) section of this guide.

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

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

#### Start Skyrim

After you have done everything above and got a clean Skyrim Special Edition installation, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace these graphics settings.
Start the game and exit once you're on the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://www.wabbajack.org/#/) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your `Desktop`, `Downloads` or `Program Files` folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will detect the optimal amount of threads at the beginning of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Click on `Browse Modlists`, and download Tales from the Northern Lands from the gallery.)
3. Once the download is done set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/Tales from the Northern Lands`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
[Post-Installation](#how-to-launch-tales-from-the-northern-lands)

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod got updated and the old files got deleted, it is impossible to download them. In this case, just wait till I update the modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto-quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected. This is a known false positive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. An example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## How to Launch Tales from the Northern Lands

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button. Under the run button, you can find a shortcut menu that allows you to make a desktop shortcut.

![launch](readme_assets/images/Launch_MO2.webp)

![run](readme_assets/images/ModOrganizer_run.webp)

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the modlist when updating!**

Additionally installed mods will be removed.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button. Make sure to do backups of your saves in case anything goes wrong.

## Controls

![ControlLayout](readme_assets/images/ControlLayout.webp)
[click here to create your own cheat-cheet, if you plan to change them](http://www.keyboard-layout-editor.com/#/gists/bfbca895e59a1682798b219aec3db158)

## In-Game MCM Options

Pre-configured.

## Other Post Installation FAQ

### Ultrawide Options

Enable the mods in the 21x9 Patches category in ModOrganizer.

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

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
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
- The team behind the Artistic Skyrim Overhaul that inspired me to make this because of it's very distinctive unique style.
- Kanjs for reviving the spirit of art-driven Skyrim Texture Overhauls.
- Nem aka. Eggy aka. Osmosis-Wrench and JanuarySnow for both helping me make some custom edits to a few mods used in this list.
- ALL the mod authors that made the mods featured in this list.
- Special thanks to all the other people listed [here](https://eziothedeadpoet.github.io/AboutMe/HALLOFFAME.html) that support this and other projects of mine.

## Contact

While I'm nearly always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/EzioTheDeadPoet/Tales-from-the-Northern-Lands/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **I WILL NOT PROVIDE SUPPORT FOR YOU IN DMs.**.

**DON'T CONTACT MOD-AUTHORS WITH ISSUES!!**

## Contributing

See [How to contribute](HOWTOCONTRIBUTE.md).

## Changelog

See [Changelog](CHANGELOG.md).

## Licenses

- [ReShade License](ReShade/RESHADELICENSE.md)

---
