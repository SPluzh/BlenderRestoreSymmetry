# Restore Symmetry

Restore Symmetry is a fork of the old **Remirror** addon for Blender.  
Its purpose is to reestablish symmetry in a mirrored mesh after sculpting (which does not always keep perfect symmetry) or other mesh editing that disrupts symmetry, while preserving UVs.

Forked from [Cyaoeu / BlenderAddons – RestoreSymmetry](https://github.com/cyaoeu/BlenderAddons/tree/master/RestoreSymmetry).

## Changes in this fork
- Works in **Blender 4.5** (tested ✅)
- Code updated to modern Blender API (2.80+)   
- Added feedback: reports how many vertices were moved 

## Installing
1. Download `mesh_restoresymmetry.py`  
2. In Blender go to: `Edit → Preferences → Add-ons → Install...`  
3. Select `mesh_restoresymmetry.py` and enable **Restore Symmetry**  

## Usage
- Select a mesh in **Object Mode**  
- Use the menu: `Object → Mirror → Restore Symmetry`  
- Or search via **F3** and type *Restore Symmetry*  
- The operation will fail if your mesh does not have a proper central edge loop.  

To add a hotkey:  
In *3D View → Object Mode* bind the operator:  `mesh.restoresymmetry`

## Authors
- Philip Lafleur — Original creator of the Remirror addon  
- Henrik Berglund — Edits to the addon  
- Sergey Meshkov — Edits to the addon  
- SPluzh - Fork updated for Blender 4.5 — modern API fixes, vertex feedback  

## License
GPL
