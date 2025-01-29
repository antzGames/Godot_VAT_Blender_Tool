# Godot VAT Blender Tool

Modified by **Abtz**

Vertex Animation add-on tested with **Blender 4.2.3 LTS**

export_mesh.glb tested with **Godot Engine 4.3**

## Changes From Original

### Vertex Animation
* Removed UE unit scale and metric system check
* Export mesh UV coords are placed at V = 0.0 instead of V = 0.5
* Frame mesh data is processed in default list order
* New **offsets.exr** and **normals.png** image files are saved into a **vaexport** subfolder in the .blend file path. 

## Description
A series of tools used to store vertex data in various ways. The data can then used in a game engine to animate meshes via a vertex shader.

### Mesh Morpher
Used to store vertex offsets between a meshes shape keys in it's UV layers. Optionally vertex normals from it's second shape key can be stored in it's vertex colors.

### Vertex Animation
Used to store vertex offsets and normals of selected mesh objects per frame into image textures.

## Getting Started
These tools can be installed as add-ons or ran as scripts. Each tool has a panel located in the 3D View's sidebar under the Unreal Tools tab.

### Installing as an Add-on
First download and unzip files into desired directory.

While in Blender open the user preferences window.

**Edit > Preferences**

Navigate the the **add-ons** tab.

Click the option to **install**.

A file browser will open.

Navigate to directory containing the tools.
    
Select the tool you want install.

Then click **install add-on**.

### Running as a Script
First download and unzip files into desired directory.

While in Blender use the text editor to open the tool you want to use.

Then either click the run script operator (the **arrow** icon in header) or use **alt+p** shortcut.

## Authors

* **Joshua Bogart**

## Acknowledgments
* Adapted for Blender from 3ds Max scripts created by **Jonathan Lindquist** at **Epic Games**.
