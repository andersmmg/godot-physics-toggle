# Godot Engine Physics Toggle Plugin
Godot 4 plugin which allows you to enable physics within the editor to help with building scenes.
Note: This plugin is for Godot 4.0, the latest version working with 3.x is commit [127a74d](https://github.com/andersmmg/godot-physics-toggle/commit/127a74d4a6c6eafee8e6b9bbb9210f4e3c7be252)

## Installation
Copy the folder addons/editor_physics into your project and activate the add-on from the Project -> Project Settings... -> Plugins menu.

## Purpose
Sometimes placing items in 3D scenes is hard, because you want an item to lay on a surface or against an item. Normally, you would manually adjust it until it looks good, which takes extra time and can still look odd. Also, you'll often see an object jump a bit when entering a scene as it adjusts itself. To fix this, I created this addon that allows you to easily toggle physics in the editor to help with creating scenes.

## Usage
Once the addon is active, a button will be added to the toolbar in the 3D workspace.

When you're ready to start simulation, just click the button to toggle the physics on the scene. Once things are how you want, make sure to click the button again to turn it back off.

## Notes
If an object isn't moving, make sure it's a RigidBody and that it's not sleeping. You can also disable sleeping on an object so it'll always be simulated when the physics is active.
