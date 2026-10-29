# Humanoid's Beam Turret Multitool with Drill [ToolCore]

## Description

This modified version of the original mod adds a **Drilling mode** to the automated multitool turret. The turret now has three complete modes:

- **Welding mode (Blue)** - Automatic welding
- **Grinding mode (Red)** - Automatic grinding
- **Drilling mode (Orange)** - Voxel drilling (NEW!)

## Features

### Technical specifications
- **Range:** 100 meters
- **Grid:** Large (1x1x1)
- **Power consumption:**
  - Idle: 0.001 MW
  - Welding: 0.5 MW
  - Grinding: 0.5 MW
  - Drilling: 0.75 MW

### Operating modes

#### Welding mode (Blue)
- Welding speed: 1.5x
- Automatic repair of damaged blocks
- Range: 100m

#### Grinding mode (Orange)
- Grinding speed: 1.5x
- Component recovery
- Range: 100m

#### Drilling mode (Orange) - NEW
- Voxel drilling (asteroids, planets)
- Automatic ore collection
- Range: 100m
- Visual effect: sparks and orange laser

### Automatic targeting system
- Rotation: 360° (±180° azimuth)
- Elevation: 180° (-90° to +90°)
- Automatically targets grids within range
- One target at a time for better precision

## Installation

1. **Required dependency:** you MUST install [ToolCore](https://steamcommunity.com/workshop/filedetails/?id=3040438530)
2. Download this mod
3. Enable it in your Space Engineers world

## Usage

1. Place the "Beam Turret Multitool" block on your grid
2. Power it
3. Use the control panel to **switch mode**:
   - **Blue** = Welding
   - **Red** = Grinding
   - **Orange** = Drilling
4. Turn the turret on - it will automatically target within its field of view

## How to switch mode

In the block's control panel:
1. Look for the "Tool Mode" option
2. Select the desired mode in the drop-down list
3. The beam color changes to show the active mode

### Tip: re-centering the turret

**To re-center the turret in a straight position:**
1. Switch mode several times - changing mode sometimes resets the turret position
2. In particular, switch to **Drill mode** and back - this is more likely to re-center it
3. Note: re-centering is not 100% guaranteed and may take several mode changes

### Technical note

**Known graphical bug:** when switching to Drill mode from Weld/Grind, the laser beam may stay visually fixed on the last targeted block. This is purely cosmetic - Drill mode works normally for drilling voxels. The beam disappears as soon as you start drilling.

## Differences from the original

This modified version adds:
- ✅ **Complete Drilling mode** with ore extraction
- ✅ ToolCore configuration optimized for the three modes
- ✅ Appropriate visual and sound effects for each mode
- ✅ Distinct color indicators (Blue/Red/Orange)

## Credits

- **Original mod:** humanoid.mp4 - [Humanoid's Beam Turret Multitool](https://steamcommunity.com/sharedfiles/filedetails/?id=3225982257)
- **ToolCore framework:** Ash Like Snow & BDCarrillo
- **Modification (Drilling):** Gwenvaël Caouissin (this mod)

## Support and issues

If you run into problems:
1. Check that **ToolCore is enabled** in your mods
2. Check that the turret has enough power
3. Make sure the mode is selected in the control panel
4. For drilling, make sure you target voxels (asteroids, planets)

## Changelog

### Version 1.0
- Added the complete Drilling mode
- Configuration of the three modes (Welding, Grinding, Drilling)
- Visual and sound effects for each mode
- Working automatic targeting system

## License

This mod is a modification of the original "Humanoid's Beam Turret Multitool" mod and uses the ToolCore framework. Respect the licenses of the original mods.