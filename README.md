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

Because Fabric doesn't really support Optifine (let's just go with no, but at least recognise the work done by Chocohead ([Curseforge](https://www.curseforge.com/members/chocohead/projects), [Github](https://github.com/Chocohead)) extending the work of [modmuss50](https://github.com/modmuss50) with Optifabric ([Curseforge](https://www.curseforge.com/minecraft/mc-mods/optifabric), [Github](https://github.com/Chocohead/OptiFabric)), a lot of where things began was with the work done by LambdAurora (https://lambdaurora.dev/optifine_alternatives/), and the list of https://github.com/LambdAurora/optifine_alternatives, and comp500's list of server side Fabric (at the time, Quilt now) mods https://github.com/comp500/quilt-serverside-mods/blob/main/README.md


Some mods are recommended only for admins, such as TabTPS, and others like SimpleHUD have a lot of their functionality captured in other mods (e.g. via Xaero and in the basic config).

Fully tuned config files are also provided, as are links to resource packs and shaders that UA really likes to run the game with.

Mojang Launcher Setup Guide

PolyMC / MultiMC Setup Guide

ATLauncher Setup Guide


## System Modules

###### System Server

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|Fabric Language Kotlin| | | | |
|FerriteCore| | | | |
|Krypton| | | | |
|LazyDFU| | | | |
|Lithium| | | | |
|LuckPerms| | | | |
|Mods Command| | | | |
|Recipe Cache| | | | |
|Starlight (Fabric)| | | | |
|TabTPS| | | | |


###### System Client

Note - Smooth Boot (Fabric) and LazyDFU achieve much the same result.  It is a matter of preference which one is installed client-side.

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|BetterF3| | | | |
|CIT Resewn| | | | |
|Cloth Config API| | | | |
|Continuity| | | | |
|Controlling| | | | |
|Disable Custom Worlds Advice| | | | |
|Dynamic FPS| | | | |
|EntityCulling| | | | |
|Fabric API| | | | |
|Fabric Language Kotlin| | | | |
|FabricSkyboxes| | | | |
|Indium| | | | |
|Iris Shaders| | | | |
|LambDynamicLights| | | | |
|LazyDFU| | | | |
|MidnightControls| | | | |
|MidnightLib| | | | |
|Mod Menu| | | | |
|Mod Settings for Fabric| | | | |
|Recipe Cache| | | | |
|Reese's Sodium Options| | | | |
|Smooth Boot (Fabric)| | | | |
|Sodium| | | | |
|Sodium Extras| | | | |


## Baseline Modules

Installed after the System sets and provide the lightest variation to the baseline vanilla experience while still delivering many improvmements.

###### Baseline Server

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|Appleskin| | | | |
|Bedspreads (Fabric)| | | | |
|BlockMeterFabric| | | | |
|Blossom| | | | |
|Cloth Config API| | | | |
|Collective (Fabric)| | | | |
|Couplings| | | | |
|CraftTweaker| | | | |
|Diggus Maximus| | | | |
|EditSign| | | | |
|Fabric API| | | | |
|FallingTree| | | | |
|Faux Custom Entity Data| | | | |
|HealthCare| | | | |
|Ingredient Extension API| | | | |
|Just Mob Heads (Fabric)| | | | |
|Just Player Heads (Fabric)| | | | |
|Kambrik| | | | |
|MAmbience| | | | |
|MidnightLib| | | | |
|Motschen's Puddles| | | | |
|Patchouli| | | | |
|Polymorph (Fabric)| | | | |
|Right-Click-Harvest| | | | |
|Simple Voice Chat| | | | |
|SleepWarp| | | | |
|Smoke Extender| | | | |
|Sound Physics Remastered| | | | |
|SpaghettiTrees| | | | |
|Styled Chat| | | | |
|Styled Nicknames| | | | |
|This Rocks!| | | | |
|Villager Death Messages (Fabric)| | | | |
|Villager Names (Fabric Version)| | | | |
|Xaero's Minimap| | | | |
|Xaero's World Map| | | | |


###### Baseline Client

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|AmbientSounds 5| | | | |
|AppleSkin| | | | |
|Bedspreads (Fabric)| | | | |
|BlockMeterFabric| | | | |
|Bookshelf| | | | |
|Collective (Fabric)| | | | |
|Compass Ribbon| | | | |
|Couplings| | | | |
|CraftTweaker| | | | |
|CreativeCore| | | | |
|Deatil Armor Bar| | | | |
|Diggus Maximus| | | | |
|Enchantment Descriptions| | | | |
|Entity Texture Features| | | | |
|Falling Leaves| | | | |
|FallingTree| | | | |
|Faux Custom Entity Data| | | | |
|Ingredient Extension API| | | | |
|Inventory Profiles Next| | | | |
|Just Mob Heads (Fabric)| | | | |
|Just Player Heads (Fabric)| | | | |
|Kambrik| | | | |
|MAmbience| | | | |
|MidnightLib| | | | |
|Motschen's Puddles| | | | |
|Patchouli| | | | |
|Polymorph (Fabric)| | | | |
|Right-Click-Harvest| | | | |
|Simple Voice Chat| | | | |
|Smoke Extender| | | | |
|Sound Physics Remastered| | | | |
|SpaghettiTrees| | | | |
|This Rocks!| | | | |
|Villager Death Messages (Fabric)| | | | |
|Villager Names (Fabric Version)| | | | |
|Xaero's Minimap| | | | |
|Xaero's World Map| | | | |


## General SMP Modules

Installed after the System and Baseline sets for gaming on SMP and Creative servers.

###### General Server

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|Adorn| | | | |
|Animal Feeding Trough| | | | |
|Architectury| | | | |
|Artisanat| | | | |
|Better Animals Plus| | | | |
|Campanion| | | | |
|Charm| | | | |
|Chirpy's Wildlife| | | | |
|Consistency+| | | | |
|Creeper Confetti| | | | |
|Creeper Overhaul| | | | |
|Croptopia| | | | |
|Culinaire| | | | |
|Dawn API| | | | |
|Decorative| | | | |
|Dehydration| | | | |
|EM4ES| | | | |
|Enriched| | | | |
|EnvironmentZ| | | | |
|Expanded Delight| | | | |
|Fabric Seasons| | | | |
|FabricAutoCrafter| | | | |
|Farmer's Delight| | | | |
|Feature NBT Deadlock Be Gone| | | | |
|GeckoLib| | | | |
|Head Index| | | | |
|hewo| | | | |
|Inv View| | | | |
|Kits| | | | |
|Macaw's Bridges| | | | |
|Macaw's Doors| | | | |
|Macaw's Fences and Walls| | | | |
|Macaw's Lights and Lamps| | | | |
|Macaw's Paintings| | | | |
|Macaw's Roofs| | | | |
|Macaw's Trapdoors| | | | |
|Macaw's Windows| | | | |
|MCA Reborn| | | | |
|Mo' Structures| | | | |
|Pehkui| | | | |
|Promenade| | | | |
|Rat's Mischief| | | | |
|Repurposed Structures| | | | |
|Server Hats| | | | |
|TacoCraft| | | | |
|TerraBlender| | | | |
|The Guild| | | | |
|Traveler's Backpack| | | | |
|ValleyCraft| | | | |
|Whisperwoods| | | | |
|Wolves With Armor| | | | |
|You're in Grave Danger| | | | |


###### General Client

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|Adorn| | | | |
|Animal Feeding Trough| | | | |
|Architectury| | | | |
|Artisanat| | | | |
|Bad Packets| | | | |
|Better Animals Plus| | | | |
|Campanion| | | | |
|Charm| | | | |
|Charmonium| | | | |
|Chirpy's Wildlife| | | | |
|Consistency+| | | | |
|Creeper Confetti| | | | |
|Creeper Overhaul| | | | |
|Croptopia| | | | |
|Croptopia's Chocolaterie| | | | |
|Culinaire| | | | |
|Dawn API| | | | |
|Decorative| | | | |
|Dehydration| | | | |
|Enriched| | | | |
|EnvironmentZ| | | | |
|Expanded Delight| | | | |
|Fabric Seasons| | | | |
|FabricAutoCrafter| | | | |
|Farmer's Delight| | | | |
|Feature NBT Deadlock Be Gone| | | | |
|GeckoLib| | | | |
|Macaw's Bridges| | | | |
|Macaw's Doors| | | | |
|Macaw's Fences and Walls| | | | |
|Macaw's Lights and Lamps| | | | |
|Macaw's Paintings| | | | |
|Macaw's Roofs| | | | |
|Macaw's Trapdoors| | | | |
|Macaw's Windows| | | | |
|MCA Reborn| | | | |
|Mo' Structures| | | | |
|Pehkui| | | | |
|Promenade| | | | |
|Rat's Mischief| | | | |
|Repurposed Structures| | | | |
|Roughly Enough Items| | | | |
|Roughly Enough Resources| | | | |
|Roughly Searchable| | | | |
|Sandwichable| | | | |
|TacoCraft| | | | |
|TerraBlender| | | | |
|The Guild| | | | |
|Traveler's Backpack| | | | |
|ValleyCraft| | | | |
|Whisperwoods| | | | |
|Wolves With Armor| | | | |
|WTHIT| | | | |
|You're in Grave Danger| | | | |


## Hardcore Modules

Installed after the System and Baseline sets for gaming on Hardcore worlds.  While some mods may allow QOL (Quality of Life) changes that might be considered cheating (i.e. anything other than pure vanilla Minecraft), they can be managed effectively through the server-side configuration files to ensure that vanilla effects are still felt for activating those specific functions / abilities / capabilities.

There are no dedicated mods that are applied beyond the baseline configuration, just specific configuration settings.

###### Hardcore Server

###### Hardcore Client


## Optional Modules

These are mods that might have originally been part of one of the above modules but removed for various gameplay or personal choice reasons.  These mods can be added without needing all players to have them installed.

###### Optional Server

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|Cooperative Advancements| | | | |
|Iceberg (Coop Advancements library)| | | | |
|Minecraft Transit Railway| | | | |
|Prefab| | | | |
|The London Underground| | | | |


###### Optional Client

|Mod|Modrinth|Curseforge|Author|Support|
|-|-|-|-|-|
|Custom Splash Screen| | | | |
|Fabric Restart| | | | |
|Minecraft Transit Railway| | | | |
|Mod Manager| | | | |
|Moderate Loading Screen| | | | |
|Prefab| | | | |
|Simple HUD Utilities| | | | |
|The London Underground| | | | |


## UA's Resource Pack & Shader Settings

