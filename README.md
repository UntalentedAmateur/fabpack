# UA's FabPack
Untalented Amateur's Tuned Fabric Mod Pack for Minecraft

Releases -> Hessian -> Calico -> Cotton -> Wool -> Satin -> Silk

This pack is separated into several modules, with distinct purposes.  You may install one or multiple module packs, with the idea that subsequent modules build on the earlier modules and are thus lighter (with dependencies already installed, etc).  The intent behind the pack is a tuned pack that provides a set of vanilla and fabric mods that have been tested to work with each other beginning with Minecraft 1.18.2 and Fabric loader...

With the issues surrounding third party access to the curseforge CDN that were experienced in May 2022, every effort has been made to ensure mods are available from both Modrinth and Curseforge wherever possible, with a preference towards Modrinth.  Mods that are only available from Curseforge will be in their own Curseforge specific modpack sections so that they can be downloaded either directly from the website, or via the Curseforge desktop application.

Modules are separated into Client and Server groups, as there are some mods that only provide functionality on one or the other side of the Client / Server set up, and there are some server configs that will override client configs if the same mod is present on both the client and the server.  Unnecesasary server mods on the client will just make the game boot slowly and bloat memory requirements as it loads modules into memory that it will never use.

If you're only wanting to play locally using the locally started server that Minecraft uses, then both are good.

In order to make sure the system isn't doing unnecessary work, the first step recommended is to set up specific instances (alternate launchers like PolyMC, MultiMC, ATLauncher), or installations (vanilla Mojang launcher).  Then, with dedicated instances / installations available, the necessary Client mods can be quickly installed and it allows for play across multiple servers where the same mods are present but are configured differently (Charm is a mod where this config pairing is critical to be aware of or else it will refuse to connect into the server).

For optimal enjoyment, it is recommended that all connecting clients to a server have the full set of appropriate client modules (e.g. System, Baseline, SMP).  Mods that can be individually activated or disabled will be identified.

Ferium / Packwiz

Because Fabric doesn't really support Optifine (let's just go with no), a lot of where things began was with the work done by LambdAurora (https://lambdaurora.dev/optifine_alternatives/), and the list of https://github.com/LambdAurora/optifine_alternatives, and comp500's list of server side Fabric (at the time, Quilt now) mods https://github.com/comp500/quilt-serverside-mods/blob/main/README.md


Some mods are recommended only for admins, such as TabTPS, and others like SimpleHUD have a lot of their functionality captured in other mods (e.g. via Xaero and in the basic config).

Fully tuned config files are also provided, as are links to resource packs and shaders that UA really likes to run the game with.

Mojang Launcher Setup Guide

PolyMC / MultiMC Setup Guide

ATLauncher Setup Guide


## System Modules

###### System Server

###### System Client


## Baseline Modules

Installed after the System sets and provide the lightest variation to the baseline vanilla experience while still delivering many improvmements.

###### Baseline Server

###### Baseline Client


## General SMP Modules

Installed after the System and Baseline sets for gaming on SMP and Creative servers.

###### General Server

###### General Client


## Hardcore Modules

Installed after the System and Baseline sets for gaming on Hardcore worlds.  While some mods may allow QOL (Quality of Life) changes that might be considered cheating (i.e. anything other than pure vanilla Minecraft), they can be managed effectively through the server-side configuration files to ensure that vanilla effects are still felt for activating those specific functions / abilities / capabilities.

###### Hardcore Server

###### Hardcore Client


## Optional Modules

These are mods that might have originally been part of one of the above modules but removed for various gameplay or personal choice reasons.  These mods can be added without needing all players to have them installed.

###### Optional Server

###### Optional Client

## UA's Resource Pack & Shader Settings

