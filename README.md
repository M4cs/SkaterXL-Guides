# Skater XL Modding Guides
A collection of guides to get you setup with Skater XL and modding for the best possible experience. If you have issues still after following the guides here please join the Official SkaterXL Modding Discord [Here](https://discord.gg/YnZc92f)

<p align="center"><img src="https://i.imgur.com/HRYYEcR.png"></p>

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
