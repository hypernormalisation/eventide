
![](https://i.imgur.com/W4qLxfX.jpg)

README UNDER CONSTRUCTION FOR 1.0!

# eventide
A Minecraft v1.16.4 modpack built upon the Fabric mod loader.
Built with an emphasis on exploration, performance, and an expansive world of tech for endgame progression.


## Installation

A multiMC client container can be found in the repository releases page:

https://github.com/hypernormalisation/eventide/releases

# Mod list
We break down the included mods by rough category below.

## Engine mods
The following mods optimse generation of world and enhance appearances.

### Lithium
A general-purpose optimisation mod for Fabric (server-only).

https://www.curseforge.com/minecraft/mc-mods/lithium

### Optifine (via Optifabric)
Optifine is a replacement render engine, enabling the use of drop-in shader packs to radically change
the look of Minecraft for the better.

See the dedicated section on shader packs below for what packs we include in the client.

https://optifine.net/home

https://www.curseforge.com/minecraft/mc-mods/optifabric

### Overworld Two
Drop-in world generator that works with Lithium and Phosphor to improve chunk generation speed by a factor of two,
at the cost of seed-reproducibility.

https://www.curseforge.com/minecraft/mc-mods/overworld-two

### Phosphor
Mod optimising Fabric's lighting engine, installed on client and server.

https://www.curseforge.com/minecraft/mc-mods/phosphor

## Quality of Life
The following mods are added to improve the everyday feel and friendliness of Minecraft.

### Appleskin
Mod showing enhanced information on food and stamina restoration.

https://www.curseforge.com/minecraft/mc-mods/appleskin

### Here's What You're Looking At (HWYLA)
Mod showing you, well, what you're looking at! With so many mods adding blocks to the game, easily seeing the
information for the block you're currently targetting is very useful!

https://www.curseforge.com/minecraft/mc-mods/hwyla

### Mod Menu
Simple in-game menu showing you what mods are installed and running.

https://www.curseforge.com/minecraft/mc-mods/modmenu

### Roughly Enough Items (REI)
Again, with so many mods, recipes can become daunting. REI provides a searchable recipe dictionary in your inventory.

https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items

### Xaero's Minimap/World Map
Minmap and world map that automatically records your surroundings. Press "M" in game for your map, "Y" for your minimap
settings (though the defaults are tweaked and sensible).

https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap

https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map

## Biome and structure mods

### Better End
Mod totally revamping the End dimension, adding a slew of colourful biomes.
We include Ender's Host's Better Nether Cities datapack for a more grandiose city generation.

https://www.curseforge.com/minecraft/mc-mods/betterend

http://www.9minecraft.net/better-end-city-data-pack/

### Better Nether
Mod totally revamping the Nether dimension, adding some lush and cold biomes to our favourite hell-world.

https://www.curseforge.com/minecraft/mc-mods/betternether

### Oh The Biomes You'll Go (BYG)
Adds a huge number of natural-feeling biomes to the overworld and to the Nether.

https://www.curseforge.com/minecraft/mc-mods/oh-the-biomes-youll-go



- Applied Energistics 2 - https://ae-mod.info/
- OptiFine, using OptiFabric
- Patchouli
- Roughly Enough Items
- Tech Reborn - https://www.curseforge.com/minecraft/mc-mods/techreborn
- Waystones - https://www.curseforge.com/minecraft/mc-mods/fabric-waystones

# Included Resource Packs

No resource packs are currently available for BYG, Better End, Better Nether, or Waystones.

As such, we use the lowest resolution available Sphax VanillaDBCraft 32x textures for 
Minecraft, Traverse, Applied Energistics 2, and for 
Tech Reborn, such that they blend in well with the packaged 16x asset textures for the above listed 
mods, without a particularly noticeable gap in quality.

# Included Shader Packs

A benefit of running lower resolution textures is the possibility to use higher-quality shaders than might have been possible with 128x assets at the same frame-rate.

We package a variety of shader packs:
- BSL - https://bitslablab.com/bslshaders/
- Chocapic 13 - https://www.curseforge.com/minecraft/customization/chocapic13-shaders
- projectLUMA - https://dedelner.net/projectluma/
- SEUS-Renewed - https://www.sonicether.com/seus/
- Sildurs Vibrant Shaders High/Extreme with Volumetric Lighting - https://sildurs-shaders.github.io/

While BSL and projectLUMA both have a reasonable performance and a pleasing appearance, they can display brightnesss flickering in foliage and other detailed textures.

Chocapic 13's liberal use of fog effects makes it the uncontested best pack to use in the Nether and End.

In the overworld where distant objects can awkwardly "pop in" during loading, Sildurs shaders' use of depth of field may result in more attractive large-scale vistas.

Switching between shaders is relatively inexpensive, so see what works for you. The default is Chocapic 13.
