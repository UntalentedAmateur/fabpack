# UA's FabPack
Untalented Amateur's Tuned Fabric Mod Pack for Minecraft

Releases will follow a simple naming convention as they undergo refinement over the different release versions:

  ``Hessian -> Calico -> Cotton -> Wool -> Satin -> Silk``

This pack is separated into several modules, with distinct purposes.  You may install one or multiple module packs, with the idea that subsequent modules build on the earlier modules and are thus lighter (with dependencies already installed, etc).  The intent behind the pack is a tuned pack that provides a set of vanilla and fabric mods that have been tested to work with each other beginning with Minecraft 1.18.2 and Fabric loader 0.14.  With the release of Minecraft 1.19, an updated version of the pack will follow in due course.

With the issues surrounding third party access to the Curseforge CDN that were experienced in May 2022, every effort has been made to ensure mods are available from both Modrinth and Curseforge wherever possible, with a preference towards Modrinth.  Mods that are only available from Curseforge will be in their own Curseforge specific modpack sections so that they can be downloaded either directly from the website, or via the Curseforge desktop application.  While Curseforge is limiting access to its own CDN, it seems open to [continuing the practice](https://support.curseforge.com/en/support/solutions/articles/9000197913-non-curseforge-mods) with non-Curseforge mods.  This particular access mode can not be guaranteed in the future, and it is neater and more efficient to create the mod pack(s) around the primary hosting location.

Modules are separated into Client and Server groups, as there are some mods that only provide functionality on one or the other side of the Client / Server set up, and there are some server configs that will override client configs if the same mod is present on both the client and the server.  Unnecessary server mods on the client will just make the game boot slowly and bloat memory requirements as it loads modules into memory that it will never use.

If you're only wanting to play locally using the locally started virtual server that Minecraft uses, then installing both the client and server packs are good (which is the "Combined" modpacks).

When downloading the releases, if you download the Source Code zips as well, it will include all of the supporting text from these Readme documents.  This isn't as much of an issue as it might appear, as it takes a snapshot of how the files appeared when the release was made.  This can help if you want to see if a mod was moved between FabPack modules, or received a version bump before its associated module was released.  Because the Readme files are written using Github's version of Markdown, you will need specific tools to present the data correctly.  There are a number of useful tools readily available:
- [Markdown Viewer](https://github.com/c3er/mdview)
- [Github Readme Instant Preview (Grip)](https://github.com/joeyespo/grip)
- [Atom](https://atom.io/)
- [A list of them here](https://github.com/mundimark/awesome-markdown-editors)

In order to make sure the system isn't doing unnecessary work, the first step recommended is to set up specific instances (alternate launchers like PolyMC, MultiMC, ATLauncher), or installations (vanilla Mojang launcher).  Then, with dedicated instances / installations available, the necessary Client mods can be quickly installed and it allows for play across multiple servers where the same mods are present but are configured differently (Charm is a mod where this config pairing is critical to be aware of or else it will refuse to connect the client to the server, and leave no trace in the logs as to why).

Examples of how to install and configure the modules using the separate Curseforge and Modrinth files are available from my [Youtube Channel](https://www.youtube.com/channel/UCCB02d_Zi_C8AX-k_6UQn9w/).  Due to its inability to handle non-Curseforge hosted content (several examples of which are present in the FabPack), the Curseforge launcher is not recommended for use.  That, and it only acts as a wrapper to then launch an instance of the Mojang launcher.  You may as well get used to modifying Mojang installations directly (examples provided on the Youtube Channel).  In order of UA's preference, the preferred Minecraft launchers are:
- PolyMC
- ATLauncher
- Mojang
- MultiMC


For optimal enjoyment, it is recommended that all connecting clients to a server have the full set of appropriate client modules (e.g. System, Baseline, SMP).  Mods that can be individually activated or disabled will be identified.

Because Fabric doesn't really support Optifine (let's just go with no, but at least recognise the work done by Chocohead ([Curseforge](https://www.curseforge.com/members/chocohead/projects), [Github](https://github.com/Chocohead)) extending the work of [modmuss50](https://github.com/modmuss50) with Optifabric ([Curseforge](https://www.curseforge.com/minecraft/mc-mods/optifabric), [Github](https://github.com/Chocohead/OptiFabric)), a lot of where things began was with the work done by [LambdAurora](https://lambdaurora.dev/optifine_alternatives/), and the list of [Optifine Alternatives](https://github.com/LambdAurora/optifine_alternatives), and comp500's list of [server side Fabric (at the time, Quilt now) mods](https://github.com/comp500/quilt-serverside-mods/blob/main/README.md)

Some mods are recommended only for admins, such as TabTPS, and others like SimpleHUD have a lot of their functionality captured in other mods (e.g. via Xaero and in the basic config).

Links to resource packs and shaders that UA really likes to run the game with are provided, and fully tuned config files and setup guides are being developed (i.e. Mojang Launcher Setup Guide; PolyMC / MultiMC Setup Guide; ATLauncher Setup Guide).

In terms of what has been used to help collate and manage the development of the packs on UA's system, the primary tools (other than the PolyMC launcher) are [Ferium](https://github.com/gorilla-devs/ferium) and [Packwiz](https://github.com/packwiz/packwiz) in their CLI variants, with manual hand adjustment of the resultant pack files.


## Performance Impact?

While UA developed the packs initially for his own edification on his local system, the consolidation and use of the packs by a wider audience began when he started admining a SMP and a Hardcore server (initially 1.18, PaperMC, but moving to 1.18.2, Fabric in due course) for a small group (2-5 SMP, 2 Hardcore) of remote players.  All players were about 450 km / 300 mi from the server location and are connecting through a variety of ISP methods.  One player is right on the limit of a 4G ISP connection, while some others play on an internal Wi-Fi network that connects to a wired domestic connection that has varied from 30mbps to 100mbps over time (and is shared with other users that stream video and other services at the same time as the SMP games are ongoing).

The individual systems that connect to the games are also variable, with a sampling including:
- 2010 iMac 21.5" 3.6 GHz Core i5 (Dual Core), 16 GB DDR3, Radeon HD5670 512MB
- 2018 Mac Mini 3.6 GHz Quad-Core i3, 16 GB DDR4, Intel UHD 630 1536 MB
- 2019 iMac 21.5" Retina 4K 3.6GHZ Quad-Core i3, 32GB DDR4, Radeon Pro 555X 2 GB

All systems are able to run the full mod packs at full screen, though individual players run different resource and shader packs.  Due to the age of at least one of the systems (the 2010 iMac), one of the supported mods has had to be rebuilt with an older linked library as it was unable to run the latest distributed version.  This is identified and provided in the appropriate location.  Even then, the oldest system was still running comfortably at 50-60+ FPS with multiple players online.

#### Server

On the server-side, running the System and Baseline modules saw a load of just under 1GB of RAM while a player was active in the server in Survival mode.  Adding the SMP Server module, and the server runs at anywhere from 2-3GB of RAM with 5 concurrent players actively in Survival.  There are occasional lag spikes, but TabTPS shows reasonable figures that can be readily improved by ongoing tuning and improvement of mod settings (for example Geyser was installed for quite a while, but has since been removed from the packs).

The Hardcore server, with approximately the same distance, is played on a 3GB server, but doesn't really go beyond 2GB of normal load.  When the server load was being assessed, the loaded mod packs were a tuned SMP set, but numerous unused modules were still being loaded into memory by both server and client.


#### Client

On the client side, it is recommended to set 4GB of RAM for a smoother experience.  The default Minecraft setting is okay, but there will be occasional client-side lag spikes and stuttering in very complicated regions and areas of high entity density.  Monitoring through BetterF3's memory module, the game doesn't seem to fully use the 4GB of allocated memory once it has loaded into the world and is running, but it does provide a nice headroom of added capacity and the game tends to hang at load if the General SMP modules  (and pre-reqs) are loaded and the RAM allocation hasn't been increased.

#### But What About?

What about mod XYZ?  Or Loader ABC?  Or Launcher DEF?  To begin with, UA hasn't had the opportunity to evaluate each and every mod that's out there and it's entirely possible that he will be adding mods to the pack over time as he finds and evaluates new mods and how they work with the existing pack elements.  There are modpacks that exist which do target the broad availability of mods, such as "All of Fabric", or "All of Forge", but UA's FabPack isn't setting out to replicate these packs.  Some mods which offer equivalent functionality to others already in the pack might have been evaluated but rejected for various reasons.  This might be due to lack of support for 1.18.2 as a starting point, lack of Fabric versions, excessively buggy behaviour, poor performance, or (in at least one case) the intentional inclusion of secret functionality that monitors game behaviour and intercepts and blocks player actions.

As to the available modloaders, UA originally started playing without any, but found that a Spigot / Paper server configuration had the plugins and addons that were really needed to deliver the gameplay that the players on that server were expecting.  From there, UA moved towards Fabric as my modloader of choice.  There is plenty that Forge has to offer, but Fabric was chosen as it closest met the requirements in terms of current and future support, functionality, and performance.  Sure, it might have fewer mods available for it overall, but it's the loader UA is going with for now.  With the recent arrival of Quilt as a fork of Fabric, expect that 1.19 and later versions of the modpack will also be tested against and work with Quilt.

With the launcher choice, UA began with the vanilla Mojang launcher and made the move to MultiMC and then PolyMC, with a side diversion into ATLauncher, as the different launchers had strengths in different areas that needed ready access during the development and evaluation phases of the modpack creation.  Launcher choice is pretty much whatever you find convenient, but UA plays with PolyMC as his daily Minecraft launcher.

## Licencing

LGPL 3.  While component mods may have different licencing (Apache, LGPL 3, Custom, MIT, etc), every effort is made to link to the source location for the relevant mods, and only offer pre-built versions for which the original mod has been forked and modified by UA (by appropriate licence); at least until the issue leading to the need for a fork has been addressed in the main code branch, usually while UA is waiting for a submitted PR to be assessed by the main mod developer.
