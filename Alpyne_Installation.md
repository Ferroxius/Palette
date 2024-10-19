# Alpyne
![Alpyne](https://github.com/user-attachments/assets/52dbccf0-45d5-4b74-89be-db2fee12c49d)

## Contents
- [System Requirements](#system-requirements)
- [FAQ](#faq)
- [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
    - [Post-Installation](#post-installation)
- [Playing and MCM Configuration](#playing-and-mcm-configuration)
- [Updating](#updating)
- [Removing](#removing)
- [Contacts](#contacts)



## System Requirements
Generally speaking this list is intended for mid-high end systems. It does not require a supercomputer however so most users should be able to run it well. 

As for my own system specifications they are as follows:
- CPU               - AMD Ryzen 5 2600 3.4GHz
- Motherboard       - ASRock b450 Pro4
- RAM               - Corsair Vengeance 16GB DDR4 3200Hz
- Storage (Main)    - Crucial P3 1TB SSD
- Storage (Backup)  - Seagate Barracude 1TB 7200RPM HDD
- GPU               - Sapphire PULSE rx6700xt 12GB VRAM
- PSU               - Be Quiet Pure Power 850W

On my pc an average of 60fps at 1080p is expected with some potential dips in more crowded locations and forests


## FAQ
### Sources of Inspiration?
[ANVIL](https://github.com/Althro/Anvil) by Althro formed the baseline of the list. Its a great starting point for modding Skyrim

A large portion of the gameplay systems and designs formed from an unreleased successor to another of Althro's lists, [Tinvaak](https://loadorderlibrary.com/lists/tinvaak-3). The list was going to be very centred around roleplaying and world responsiveness

Modlists such as Styyx's [Ruvaak](https://github.com/Styyx1/Ruvaak-Readme) were inspirations for the dark fantasy approach

### Why isn't (Insert mod here) included?
Usually I do not include a mod for the following reasons:
- It goes beyond the intention of the list
- It possesses technical and/or compatibility issues
- It is simply something I'm not personally interested in

I am open to suggestions but if you do wish to make one then keep in mind the above criteria

### Can I add/remove mods?
You're welcome to do so and can also use this list as a baseline to build off of if you wish. Keep in mind however that you will need to be responsible for things like Conflict Resolution as my help will be limited

### Widescreen Support?
I don't personally own a widescreen monitor so I am unable to test and properly support widescreen. Community support may help in this matter however

### GOG Support?
I don't own Skyrim on GOG so I am unable to test and properly support it

# Installation
## Pre-Installation
**Base Requirements**
- Skyrim Anniversary Edition + DLC Upgrade on Steam (Clean reinstall required)
- Latest version of windows 10
- A nexus mods account (Premium is recommended by Wabbajack to automate installation but you can use a free one)
- Latest NVIDIA/AMD Drivers
- 215GB of storage space available in total approximately. Some extra headroom is recommended for Wabbajack so I would recommend at least 200GB

**MO2 Requirements**
- [Latest Microsoft Visual C++](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- [Latest .NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework)

**Setting up Skyrim**
- Confirm first that you are on the latest version of Skyrim (version 1.6.1170). You can check by going to SkyrimSE.exe, right-clicking and selecting **Details**
- Launch Skyrim at least once. This is to allow it to generate important ini files as well as make sure you've downloaded all CC

**Set the game language to English**
This is a temporary measure as Wabbajack requires the english version of the game to work correctly. You can revert the language back after installation

## Wabbajack Installation
**Installing Wabbajack**
Download [Wabbajack](https://www.wabbajack.org/)
- Extract the file and place it in an easy to access location. DO NOT however place it inside any UAC controlled folders e.g. Program Files, Program Files (x86), Downloads, Documents, etc.
- For reference my wabbajack location is C:\Games\Modding\Wabbajack
- Double click wabbajack.exe and let the program update itself if needed

**Downloading and Installing Alpyne**
Go to the releases section on the right side of this github page. Find the latest release of Alpyne and download its wabbajack file. Open it and it will present you with the installation window.
In the installation window, you will be asked to define the locations of two folders:
- Installation Location which is where Alpyne will be installed. Choose an easy to access folder such as C:\Games\ that is outside UAC protected folders (Program Files, Documents, etc).
- Download Location which is where the downloaded mod archives will be stored. The default location is within MO2s downloads folder but if you want you can set it to an external folde
- Once the folder locations have been set click the button on the right to start installation

Now wabbajack will begin installing the list. If you have a nexus premium account this will be automatic so sit back and wait. If you have a normal account however you will need to download each mod manually. Wabbajack will make this easier for you though by showing the download page instantly, you just need to click download is all

**Troubleshooting Wabbajack**
If Wabbajack idles or fails installation the first thing I would suggest is just restart Wabbajack. It'll pick up right where it left off and you wont lose any progress

If Wabbajack continues to have trouble then I'd suggest joining Aetherius modding (Link in [Contacts](#contacts)) and finding the beta modlists channel to inquire there

## Post-Installation
Open up Mod Organizer 2. Everything should be installed and generally shouldnt require any tweaking unless you plan on modifying the setup

To start the game select Alpyne in the top right drop down menu and click Run. Skyrim should launch not too long afterwards
- NOTE: Alpyne is not built on the latest version of Mod Organizer 2. The program has the option to update in the menu but it is not recommended to do this as the list could be broken after updating.

## Playing and MCM configuration
When you start a new game you will be presented with an option to skip the intro. This is Optional Quick Start. If you choose No the vanilla intro sequence will play out as normal, if you choose Yes you will spawn at the exit to Helgen Keep and will continue from there. Note that the vanilla intro will always be a bit janky so play through it at your own risk of it breaking.
- If you choose to skip the intro, a chest can be found after exiting Helgen cave that gives you a number of scrolls to use as a starting "class". Choose one, multiple or none if you wish and use it to acquire some items and buffs

In Mod Configuration there are a few available to use. The list doesn't currently follow any specific settings so configure the mods however you wish

## Updating
Updating is very similar to installing the list. Simply make sure your paths are the same and tick the overwrite existing modlist button. 
Some things to keep in mind:
- Any mods you have added will be deleted when updating.
- Its recommended to back up your saves. You may need to start a new game after some updates. I'll notify in the changelog if this is needed.

## Removing
Simply delete the folder containing the modlist

## Contacts
I am primarily found at [Aetherius Modding](https://discord.gg/aetherius-modding)
