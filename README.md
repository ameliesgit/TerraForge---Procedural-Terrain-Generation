# TerraForge---Procedural-Terrain-Generation
TerraForge is a Blender add-on for procedural terrain generation built in Python. It lets you generate detailed, varied landscapes directly in Blender without manual sculpting. 

## Features
Multiple biome presets with individual surface characteristics
Adjustable parameters for topology, detail level, and biome blending
Easy asset integration for vegetation, rocks, and other objects directly onto generated terrain
Designed for rapid iteration within a standard Blender workflow
Based on and extending the A.N.T. Landscape add-on (GPL v3)

## Installation
Download TerraForge.zip
Open Blender and go to Edit > Preferences > Add-ons
Click the dropdown arrow in the top right corner and select Install from Disk
Select the downloaded TerraForge.zip
Enable the add-on by checking the checkbox next to TerraForge
The add-on panel will appear in the 3D Viewport sidebar (N-panel) under the TerraForge tab

## Usage
### Getting Started
Open the Terra Forge panel in the 3D Viewport sidebar (N-panel). Click the About / Help button for an in-app overview.

### Terrain Mode
The main mode for generating landscapes. Adjust parameters for topology, surface detail, biomes, and water/ice level. Vegetation always spawns above the water level automatically — except seagrass, which spawns below it.

### Planet Mode
A more rudimentary mode for generating spherical planetary bodies with basic terrain displacement.

### Adding Custom Assets
To use your own vegetation, rocks, or other objects, place them in a Blender Collection first. TerraForge will then be able to reference and scatter them across the terrain.

### Materials
Basic procedural materials are included for terrain and water/ice. These work with Cycles only and can be swapped out for custom materials

### Performance
A vertex count display and performance indicator are shown in the panel. Use the built-in subdivision presets to balance detail and performance and avoid crashes on lower-end hardware.


## License
GNU General Public License v3.0, see LICENSE file for details.

## Last Updated
May 2026
