# Fahdon - A Skyrim Together Experience

![Fahdon Splash](https://user-images.githubusercontent.com/88156705/180282286-80068007-10d7-434c-b55a-75e2a0e6609f.png)

Wabbajack Modlist Installer by Chef

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Fahdon](#downloading-and-installing-fahdon)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [Creation Club ESL to ESM](#Creation-Club-ESL-to-ESM)
    - [Skyrim Together Reborn](#Skyrim-Together-Reborn)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating Fahdon](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble
Designed specifically with Skyrim Together Reborn in mind, each mod has been personally playtested and checked for desync issues and other general inconsistencies in multiplay. If you are looking for an experience inspired by systems found in Tabletop RPGs (i.e. D&D) then this is the list for you and your friends. You will benefit greatly from each person choosing a role through the [Set of Skills](https://www.nexusmods.com/skyrimspecialedition/mods/55535) MCM which will allow you to build into a specific archetype and gain benefits that can be boons to your party.

Also, if you are into light or heavy RP, Fahdon has the tools to cultivate your inner storyteller. From [in-game emotes](https://www.nexusmods.com/skyrimspecialedition/mods/22960) to [immersive spell learning](https://www.nexusmods.com/skyrimspecialedition/mods/71565), this list will have a little something for everyone.

Enemies are smarter and will quickly overwhelm you if you aren't careful, so be sure to plan well and equip your group before adventuring. 

As there are a lot of sights to see, you may want to prep yourself for a long journey. Be it to the northernmost county of Cyrodiil, [Bruma](https://www.nexusmods.com/skyrimspecialedition/mods/10917), or perhaps finding yourself whisked away into a [Dark and Mysterious land](https://www.nexusmods.com/skyrimspecialedition/mods/10423), you'll never be want for places to explore.

Full modlist [here](https://loadorderlibrary.com/lists/fahdon-a-skyrim-together-experience-1).

> <ins>**"WARNING: FAHDON REQUIRES THE *FULL AE UPGRADE*, PLEASE ENSURE YOU HAVE PURCHASED THE FULL UPGRADE."**</ins>

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

Fahdon uses AVO AE's graphical base and has been tested extensively on a range of systems and using industry standard testing software to determine the required specs for the list. As such, the following specs are recommended to run the list.

| Spec Category | Minimum for 30fps | Recommended for 60fps |
|     :---:    |     :---:      |     :---:     |
| **CPU**   | 6 core/thread @ 2.3Ghz. i9-9600t or better. | 8 Core/16 Thread CPU. i9-9900k or better. |
| **Video Card**    | 6GB Vram clocked between 1290 and 1390. If you have an overcloked model with 4GB (such as a GTX 1060 laptop), you may be able to run it. A card such as the GTX 1060 would work for this. | 8+GB VRAM, but no more than 10 needed, clocked between 1400 and 1500. A card such as a GTX 1080 or 1080ti or better would be ideal.      |
| **Ram**    | 6GB DDR5 with some stuttering.      | 8-10GB DDR5 for smoothest experience. 16GB DDR4/5 advised.     |
| **With ENB**     | +15% to required resources.       | +10% to required resources.      |
| **Expected peformance**    | 35fps outdoors wiith 40+ indoors. Loading times between 20 to 30 seconds.       | 59-112fps outdoors and indoors with loading times around 10 to 15 seconds. Cap FPS to achieve smoother experience.      |
| **Expected non ENB performance**    | 40fps outdoors with 50fps indoors. Loading times between 15 and 40 seconds.      | 100+ fps both outdoors and indoors with loading times between 5 and 15 seconds.     |

Space required: Approx 140GB (Without Downloads) 149GB (With Downloads)

## Installation

Installing Fahdon is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Fahdon, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the games to the main menu in order to download all the creations.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Fahdon

Downloading and installing Fahdon can take a while depending on your internet connection and computer. To install Fahdon, complete the following steps.

1. Open Wabbajack and click on browse modlists, ensure that Unofficial Lists is checked.
2. Press the download button on Fahdon and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Fahdon. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

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

## Post-Installation

### Game Folder

Fahdon uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.

### Creation Club ESL to ESM

Due to the Skyrim Together Reborn team disabling the ESL Reader, I've had to include a .BAT that you will have to run in order to convert the plugins to their correct extensions as outlined below:

1. Open up MO2 and find the Divider labeled "Master Files".
2. Inside the Divider you will find a mod named "CC AE Converted (STR Compatible)".
3. Right click on the mod and select "Open in Explorer", which will then open up Windows Explorer.
4. Double Click the folder named "Extensions BAT" to open it.
5. Ctrl + X to cut the file from the folder, then return to the main folder and paste it using Ctrl + V
6. Double Click on the Extension Converter.bat to run it. You should see all the .ESLs turn into .ESMs.
7. Refresh or restart Mod Organizer 2. If you see that the CC plugins have been converted in the plugins tab, continue to the next step.
8. Now go back into MO2, click on the "Restore Backups" tab on the right pane above your plugins. (The one which looks like a swooping arrow)
9. Select the backup (there should only be **one**, if there isn't, choose the latest.) and all the ESMs should be loaded correctly:
![image](https://user-images.githubusercontent.com/88156705/194963545-9a56cade-f759-434a-8c4c-df0436f30a85.png)
10. Hit Refresh in Mod Organizer 2 if the backup doesn't immediately change the load order.



### Skyrim Together Reborn

As it has been wonderfully documented by the STR team already, please continue to: [Skyrim Together Reborn](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/skyrim-together-reborn/launching-skyrimtogether-through-mo2) for the initial setup of your STR client.

> **NOTE:** Due to using Stock Game, please navigate to where you installed the modlist, open up the Game Root folder and select the SkyrimSE.exe inside. This is a **VERY IMPORTANT STEP**. If you use your actual install directory for Skyrim SE, the modlist **WILL NOT WORK**.

### ENB
Fahdon is designed for use with an ENB and comes with [Mythical Ages](https://www.nexusmods.com/skyrimspecialedition/mods/11578) & [Rune ENB](https://www.nexusmods.com/skyrimspecialedition/mods/68138), already activated and ready for use. I've included an optional ENB that can be changed via ENB Organizer, which is: [The Vanilla ENB 2](https://www.nexusmods.com/skyrimspecialedition/mods/78124)

If you wish to install your own ENB, however, an ENB manager is included. Simply put your new ENB into a seperate folder in `Fahdon\tools\Enb Organizer\Games\SkyrimSE\Preset`.

#### Using ENB Manager

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big `Run` button next to it. Run the program named `Pick Your ENB` from Mod Organizer 2. The images below do not represent the settings in Fahdon. **These serve as general examples**.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%201.png?raw=true)

If the image below comes up, simply press OK. It is nothing to be concerned about.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/Ignore%20Warning.png?raw=true)

Navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%203.png?raw=true)

Activate the ENB you wish to use by pressing the slider. To deactivate it, simply press the slider.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%205.png)

For adding your own presets and more details, take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Skyrim Together` and press the `Run` button.

### In-Game MCM options

Fahdon utilizes [MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719) by the lovely MrowPurr and does not require modification. If you wish to make any modifications to the MCM, **be sure to disconnect before touching the MCM and sync all changes with your other party members.**

### Starting the Game

- Fahdon uses [Alternate Start - Live Another Life](https://www.nexusmods.com/skyrimspecialedition/mods/272).
1. Create your character and let MCM Recorder Load everything.
2. Feel free to explore the Starting Prison. There are a number of supplies to get you started.
3. Choose an Alternate Start.
4. Go into the [Set of Skills](https://www.nexusmods.com/skyrimspecialedition/mods/55535) MCM and select your starting class.
5. Go into your inventory and use the "Choose Your Destiny" scroll to complete your starting skill choices.
6. Once you have chosen your desired start and left the starting cell, open the MCM and navigate to the WeapSpeedMult Fix MCM. Ensure that the Weapon Speed Multiplier Fix is activated. If it is not, enable it. You will have to unequip any weapon you currently have equipped before doing so. **THIS IS NOT OPTIONAL**.
7. Press F2 to open the Reborn UI and connect to your server!
8. Have fun!
	
## Adding mods to Fahdon

I will not be supporting the addition of mods in any official capacity due to the complexicity and testing each mod requires in order to determine it's compatibility with the STR client and syncing with other players.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

Placeholder for your Readme.

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [The Animonculory Server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/Para0x/Fahdon-A-Skyrim-Together-Experience/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

## The Animonculory Team
- Althro - Leader & Head of Development
- Styyx - Senior Management Team & Dev Team
- Chef/Para0x - Senior Management Team & Dev Team
- The Spaniard -Senior Management Team & Documentation
- GuitarBarbarian - Senior Management Team
- Annakins - Dev Team, Testing, Graphics & Documentation
- Astro - Dev Team & Testing
- Abandoned_by_Arkay - Testing
- DestinySlayer - Dev Team & Community Engagement
- Skyrim Together Reborn Team - Without them, this project would not be possible. Huge thanks to them.
