
# Basic Editor Overview #

## Table of Contents ##
- [[#Getting to the Level Editor]]
- [[#Editor Screen Overview]]
	- [Layers](#Layers)
	- [[#<u>Selection</u>|Selection]]
	- [[#<u>Alternate Selection</u>|Alternate Selection]]
	- [[#<u>Menu</u>|Menu]]
- [[#Basic Editor Controls]]
## Getting to the Level Editor ##
The Level Editor is located in the top right of the **Main Nexus**. Type a level name and hit `OK`
![Level Editor](../../Resources/Videos/Level_Editor_Open.webp)

The Level Editor will be where you will spend your time making levels. Levels are saved in your `Dustforce/user/level_src` folder.  

Note:
- Level names need to be **Less than 24 characters** otherwise in-game leaderboards won't display properly. They will still display on [Dustkid](https://www.dustkid.com)!
- If you rename the file it **will not** rename the level-in game. (See [Level Settings](Level%20Settings.md) to learn more)
## Editor Screen Overview ##
Once loaded into the Level Editor, there are a few areas of interest
![Screen Overview](../../Resources/Images/Editor_Overview.png)
### Layers ###
Dustforce Levels are broken up into different layers. Each layer(s) have different properties but adhere to similar rules. You can toggle each layer's visibility by clicking the corresponding first box, and you can lock each layer by clicking the corresponding second box (locked from edits).

- Layers 1-5 - Backdrop Layers
	- Only Props can be placed on layers 1-5
	- Props on these layers will be larger and parallax slower
- Layers 7-11 - Parallax Layers
	- Tiles or props on these layers give a sense of distance
	- The lower the layer the slower the parallax will be (further it will feel)
- Layers 12-17 - Background Layers
	- Tiles or props on these layers move at the same rate as the collision layer
- Layer 18 - Player and Entities Layer
	- All entities will be placed on this layer regardless of what layer you place them on
	- Props placed on this layer will act if they were placed on layers 12-17
- Layer 19 - Collision Layer
	- All tiles placed here will be collidable with the player and entities
	- Props placed on this layer will act if they were placed on layers 12-17
- Layer 20 - Foreground Layer
	- Tiles or Props placed here will be *in-front* of the other layers

*Note: Layers I, C, T, 21, 22, and 0 are Dustmod specific layers and are described in [Layers](Layers.md)*

#### <u>Selection</u> ####
The Selection part of the editor allows you to choose what **type** of tile, prop, entity that you want to place depending on what mode is selected in the menu. 

*Note: When placing the tile, prop, or entity, it will be placed on the selected layer.*

#### <u>Alternate Selection</u> ####
Depending on the selection, there may be alternative options. For tiles, and props these alternative options are just slight color variations. Triggers are further described in [Triggers](Triggers.md) and scripts are further described in [Scripts](Scripts.md)

*Note: When selecting a variant, it acts as a completely separate tile and will not blend next to other variants of the same tile*

#### <u>Menu</u> ####
From the menu, you can choose what "mode" you are in. From there your Selection and Alternate Selection parts of the editor will change to match the mode.

The Modes are:
- [Selection](Selection.md)
- [Tiles](Tiles.md)
- [Props](Props.md)
- [Entities](Entities.md)
- [Triggers](Triggers.md)
- [Camera](Camera.md)
- [Emitters](Emitters.md)
- [Level Settings](Level%20Settings.md)
- [Scripts](Scripts.md)
- Help (*Good for a quick reference guide if you need any reminders regarding shortcuts*) 

## Basic Editor Controls ##
These along with other useful shortcuts can be viewed at anytime by clicking the **?** icon in the menu.
- `TAB` to enter and exit "Editor Mode"
- `CTRL + S` to save the file (*USE OFTEN!*)
- `SPACE + Leftclick` to pan the screen
- `SPACE + MouseWheel` to zoom the screen
- `Rightclick` to delete  (*Note: Dependent on what you have selected, tiles delete tiles, entities delete entities*)
- `CTRL + Z | CTRL + Y` Undo / Redo


