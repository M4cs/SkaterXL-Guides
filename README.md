# Skater XL Modding Guides
A collection of guides to get you setup with Skater XL and modding for the best possible experience. If you have issues still after following the guides here please join the Official SkaterXL Modding Discord [Here](https://discord.gg/YnZc92f)

<p align="center"><img src="https://i.imgur.com/HRYYEcR.png"></p>

#### Table of Contents
#### I. [Setting Up Your Game](https://github.com/M4cs/SkaterXL-Guides#setting-your-game-up-for-mods)
#### II. [Installing Mods](https://github.com/M4cs/SkaterXL-Guides#installing-mods)
  1. [Getting Started](https://github.com/M4cs/SkaterXL-Guides#getting-started)
  2. [Installing UMM](https://github.com/M4cs/SkaterXL-Guides#installing-unitymodmanager)
  3. [Installing XLShredMenu](https://github.com/M4cs/SkaterXL-Guides#installing-xlshredmenu)
  4. [Installing Other Mods](https://github.com/M4cs/SkaterXL-Guides#installing-other-mods)
  5. [Recommended Mods](https://github.com/M4cs/SkaterXL-Guides#working-v3-mods)
#### III. [Installing XLMultiplayer](https://github.com/M4cs/SkaterXL-Guides#installing-xlmultiplayer)
#### IV. [Setting Up a Server](https://github.com/M4cs/SkaterXL-Guides#setting-up-a-multiplayer-server)

# Setting Your Game Up For Mods

When you first download SkaterXL it will be running the stable v2 version. Most mods are not stable/compatible with that version anymore so you need to update to a beta build.

To do so open Steam and right click on the SkaterXL title (yours will **not** say `[beta]` on it):

<p align="center"><img src="https://i.imgur.com/hdbvSyC.png" /></p>

Then click on Properties > Betas and from the beta drop down select `beta - public beta builds`:

<p align="center"><img src="https://i.imgur.com/Sk3ELSy.png" /></p>

Your game will update but this shouldn't take too long.

Run the game once and confirm that it says `v0.3.0.0b` in the lower left corner:

<p align="center"><img src="https://i.imgur.com/jOxYvvZ.png" /></p>

After this you should be ready to start installing mods!

# Installing Mods

### Getting Started

First, there are some requirements to setting up SkaterXL for modding. You are going to need UnityModManager and the XLShredMenu to get started. Most mods depend on XLShredMenu and UMM (UnityModManager) is an easy way to keep track of/install your mods. 

**[UnityModManager Download](https://www.dropbox.com/s/wz8x8e4onjdfdbm/UnityModManager.zip?dl=1)**

**[XLShredMenu Download](https://cdn.discordapp.com/attachments/702182609077141997/702191357321543830/XLShredMenuMod-0.0.5.zip)**

### Installing UnityModManager

Download the `.zip` from the link above and extract it somewhere you can access it easily. Then double-click the UnityModManager.exe file which should open up a window that looks like this (SkaterXL will not be selected by default):

<p align="center"><img src="https://i.imgur.com/2Mod47q.png" /></p>

Select SkaterXL in the Game dropdown, and then click the Folder area which will allow you to browse. Find your game's **ROOT PATH** which will usually be in `steamapps/common/SkaterXL`.

Now click **Install** and switch to the Mods screen.

### Installing XLShredMenu

Download the XLShredMenu `.zip` from above and drag it onto the UnityModManager window where it says `Drop Zip Files Here`. **You do not have to do anything extra when installing mods, only this and if it says SUCCESS at the bottom, it worked.**

### Installing Other Mods

**Most** mods work by just dragging and dropping onto the UnityModManager window like with XLShredMenu. **XLMultiplayer does not work the same way. It comes with an installer so please follow the guide below for installing that.**

## Working v3 Mods:

[XLShredMenu](https://github.com/blendermf/XLShredLoader/releases/tag/menu-mod-0.0.5) - [GitHub](https://github.com/blendermf/XLShredLoader/) by [blendermf](https://github.com/blendermf)

[Babbo Settings](https://github.com/andreamatt/Skater-XL-mods/releases/tag/BabboSettings_v0.6.8) - by [andreamatt](https://github.com/andreamatt)

[Sound Mod](https://github.com/andreamatt/Skater-XL-mods/releases/tag/SoundMod_v0.0.3) - by [andreamatt](https://github.com/andreamatt)

DawgVinci's Mods - Join the [Discord](https://discord.gg/YnZc92f) and checkout `#v3-mods` for links to these! They include map fixes, extensions required by some maps, stats modifiers and much more needed for a better experience!

# Installing XLMultiplayer

[silentbaws](https://github.com/silentbaws) made a mod for SkaterXL which allows players to play together in online servers. You can do so by following the instructions below:

First download [XLMultiplayer](https://github.com/silentbaws/XLMultiplayer/releases/tag/v0.8.1). Unzip the contents to somewhere like your Downloads folder.

**Run the Installer inside of the folder you just extracted. Do not drag anything to UnityModManager.**

A window with a BIG button saying `Install` will pop up. Click that and confirm or select your SkaterXL **ROOT** directory (`...\steamapps\common\SkaterXL`)

Now XLMultiplayer will be installed. Press `P` to open the menu. Once in a server press `Tab` to hide the chat, `P` again to disconnect, and `M` to vote for a map.

#### My Public Servers Mod for XLMultiplayer

I made a mod for XLMultiplayer which will allow more servers to show up in the server browser when you open up the menu. To install it download the 2 DLL files from [here](https://github.com/M4cs/XLMultiplayer/releases/download/0.8.1-psmc-0.1/XLMultiplayerPSMClient.zip). Replace the XLMultiplayer.dll and XLMultiplayerUI.dll files inside of `steamapps\common\Skater XL\Mods\XLMultiplayer`. This will allow you to view servers running the XLMultiplayer PSM Server mod. More info on hosting servers with that can be found below in the Hosting a Server section.

# Setting Up a Multiplayer Server

Download `Server.rar` from [here](https://github.com/silentbaws/XLMultiplayer/releases/tag/v0.8.1) and un-rar it somewhere on your computer. It only runs reliably on Windows but if you can figure out a way with Wine on Linux please contribute here!

Setup your ServerConfig.json with a name, MOTD, and max players.

Next you need to change `EnforceMaps` to TRUE. Then you need to make a directory in the same folder called `Maps`. This is where you will put all of your server's maps. If you are running it on a computer where you also play SkaterXL you can put the full path to your Documents Maps folder so something like `C:\Users\<YOUR NAME>\Documents\Skater XL\Maps\` as the `Maps` path in ServerConfig.json.

Double click the XLMultiplayerServer.exe file and it should start to run. You will need to port forward `7777` and `7778` by default. **If you change your ports, you need to port forward that port and the number above it. So if you change to `1234` you need to PF `1234` and `1235`.** XLMultiplayer uses UDP packets so if you need to port forward for a certain type choose UDP.

### My Server Doesn't Show Up In The Browser!!

The normal XLMultiplaye server does not show all servers in the browser by default. I have made a fork of it to fix that so anybody using the Public Servers Mod client will be able to see them. Read above for info on obtaining the client mod. To install the server mod download the `XLMultiplayerServer.zip` from [here](https://github.com/M4cs/XLMultiplayer/releases/tag/v0.8.1-psm-0.1). Replace the files inside of your current XLMultiplayer server directory with the ones in the zip except `ServerConfig.json`. Now when you start your server you will be visible to everybody using the PSM client!
