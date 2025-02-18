# Changelog

All notable changes to this project will be documented in this file.

## [1.3.0] - 2025-01-22

### Added

- Whitewashed cobblestone
- Half timbered blocks
- village structure:
  - quarryman house (plains village)
  - quarryman house (plains zombie village)
  - forest botanist house (plains zombie village)
  - forest botanist house (taiga zombie village)
- windows
  - fixed: Fixed Window, Double Fixed Window, Fixed Cross-Window
  - openable: Window, Double Window, Cross-Window
- shelves
- sword holders
- signposts

### Changed

- Redstone lanterns and Redstone lamps can now be hung on wired chains placed horizontally. They then connect to the wired chains and receive a Redstone signal from the wired chains.
- Forest botanist
  - Trade offer changed in consideration of the wandering trader.
  - At the "Journeyman" level, the forest botanist now potentially also sells cocoa beans.
- structures "forest botanist house (plains village)" and "forest botanist house (taiga village)" optimized

### Fixed

- Recipe advancements of the block variants corrected.
- Loot table of the block variant slabs corrected.
- Server-side drill press recipe bug fixed.


## [1.2.0] - 2024-12-17

### Added

- Stairs and slabs added for most block variants.
- Bone pile, bone pile with skull and bone pile with sword
- Wired blocks can now also be crafted from the following blocks:
  - Acacia Log, Birch Log, Block of Bamboo, Cherry Log, Crimson Stem, Cypress Log, Dark Oak Log, Jungle Log, Mangrove Log, Oak Log, Spruce Log, Warped Stem
  - Stripped Acacia Log, Stripped Birch Log, Stripped Block of Bamboo, Stripped Cherry Log, Stripped Crimson Stem, Stripped Cypress Log, Stripped Dark Oak Log, Stripped Jungle Log, Stripped Mangrove Log, Stripped Oak Log, Stripped Spruce Log, Stripped Warped Stem
- seating furniture:
  - chairs
  - benches
  - poufs
- structures:
  - tower 1, tower 2, tower 3 (each in various configurations)
  - forest botanist house
- village structure:
  - forest botanist house (plains village)
  - forest botanist house (taiga village)

### Fixed

- Methods "mirror" and "rotate" added to: AbstractLitFacingShapeBlock, AbstractTwinWireMeshFenceBlock, AbstractTwinWireMeshFencePostBlock, SpikesBlock, TableBlock, TableWiredBlock, TwinWireMeshFenceSecurityBlock, TwinWireMeshFenceSecurityCornerBlock, WallRazorWireBlock


## [1.1.0] - 2024-11-14

### Added

- torch button
- soul torch button
- rotary switch
- spikes blocks
- Added more Jaw Crusher recipes to be able to craft "normal" Minecraft blocks/items in the Jaw Crusher. E.g. stone to gravel.
- more MME story advancements
- wall razor wire

### Changed

- The probability of sapling dropping from leaves changed (firethorn / privet / sloe).
- Fortune now increases the probability of sapling dropping from leaves (cypress / firethorn / privet / sloe).
- Some tooltips extended / optimized.
- Twin wire mesh fences: CollisionShape height reduced from 1.5 blocks to 1 block.

### Fixed

- Missing repeating block textures added.
- Correction of messages that are displayed when a player dies by razor wire, firethorn, sloe or prickly pears.
- recipe advancement "steel_wire_mesh_from_steel_ingot_mm" corrected
- bronze wire mesh &  iron wire mesh: tag "needs_iron_tool" removed


## [1.0.0] - 2024-10-13

### Added

- advancements
- loot table modifications
  - chests 
    - village_armorer
    - village_temple
    - village_toolsmith
    - village_weaponsmith
  - entities
    - creeper
    - drowned
    - skeleton
    - zombie
  - plants
    - cactus
- new villager professions
  - forest botanist
  - quarryman
- latex
  - latex bucket
- sulfur
  - sulfur ore
  - deepslate sulfur ore
  - nether sulfur ore
  - sulfur nugget
  - crushed sulfur
  - sulfur block
  - ...
- tin
  - tin ore
  - deepslate tin ore
  - raw tin
  - tin ingot
  - crushed tin
  - tin block
  - ...
- mediterranean cypress
  - cypress log
  - cypress wood
  - cypress planks
  - ...
- firethorn
  - firethorn log
  - firethorn leaves
  - firethorn leaves with blossoms
  - firethorn leaves with berries
  - ...
- privet
  - privet log
  - privet leaves
  - privet leaves with blossoms
  - privet leaves with berries
  - ...
- sloe
  - sloe log
  - sloe leaves
  - sloe leaves with blossoms
  - sloe leaves with berries
  - ...
- drill press
- jaw crusher
- latex collector
- milling machine
- table saw
- box end wrench
- cross head screwdriver
- steel axe
- steel hoe
- steel pickaxe
- steel shovel
- steel sword
- voltmeter
- bronze
  - raw bronze mixture
  - bronze nugget
  - bronze ingot
  - ...
- luminous metal
  - raw luminous metal mixture
  - luminous metal ingot
  - luminous metal nugget
  - ...
- plastic
  - white natural rubber-sulphur-mixture
  - block of white plastic
  - ...
- red alloy
  - raw red alloy mixture
  - red alloy ingot
  - red alloy plate
  - ...
- red alloy red sand
- red alloy sand
- steel
  - raw steel mixture
  - steel ingot
  - steel nugget
  - ...
- crushed coal
- crushed copper
- crushed diamond
- crushed iron
- diamond circular saw blade
- drill bit
- milling cutter
- milling machine base
- milling machine turret
- red alloy cable
- plates
- wires
- block variants
  - block with dot relief
  - block with double meander ornament
  - block with FSM
  - block with golden double meander ornament
  - block with golden FSM
  - block with golden inscription
  - block with inscription
  - block with lapis double meander ornament
  - bricks
  - dented block
  - framed block
  - helix block
  - maze block
  - parquet (herringbone)
  - pavers (zigzag)
  - S-bricks
  - small bricks
  - small tiles
  - tile framed block
  - tiny bricks- chains
- doors
- horizontal isolated doors
- vertical isolated doors
- secret doors
- secret trapdoors
- pressure trapdoors
- trapdoors
- wired blocks
- repeating blocks
- signal randomizer blocks
- wired chains
- wired fences
- red alloy glasses
- chimneys
- redstone chimneys
- creeper statues
- cross statues
- cross with bar statues
- guard with axe statues
- guard with sword statues
- moia statue
- trident statue
- twin wire mesh fences
- twin wire mesh fence gates
- twin wire mesh fence gate tops
- twin wire mesh fence gate top waves
- twin wire mesh fence posts
- twin wire mesh fence half posts
- twin wire mesh fence tops
- twin wire mesh fence top waves
- twin wire mesh fence razor wires
- twin wire mesh fence razor wire corners
- wire meshs
- tables
- wired tables
- lanterns
- soul lanterns
- wall lanterns
- wall soul lanterns
- redstone lanterns
- luminous panels
- redstone-luminous panels
- wall / ceiling lamps
- redstone wall / ceiling lamps
- floor lamps
- redstone floor lamps
- table lamps
- redstone table lamps
- chandeliers
- redstone chandeliers
- sconces
- redstone sconces
- green prickly pears
- red prickly pears
- sloe berries


<!--
DUMMY SECTION:

## [X.Y.Z] - YYYY-MM-DD
### Added
- ...
### Changed
- ...
### Fixed
- ...
### Removed
- ...
### Deprecated
- ...
-->
