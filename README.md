[![Godot Engine logo](/logo.png)](https://godotengine.org)

## HomeWorld Godot

##### Introduction

This project aims to add features we lacked during our game developments

##### Features

Each added features, should be found in its own branch for easier cherry picking

Here is a quick overview of added features:
- branch:planemesh2d =>`PlaneMesh2D` <br>act just like PlaneMesh but its normal points towards the camera allowing its use in 2D
- branch:tiledata-swap =>`TileSet.tile_swap_with_id(int ida, int idb)` <br>give tileset the ability to swap tile order

- branch:3.2-monkey-fix-linux-clean => Add a delay to driver init with a big print for linux to avoid later race condition.
- branch:audio-fix-get-recording-cowdata => Solve a hard crash on AudioEffectRecord::get_recording() as well as move the encoding to its own thread for performance reasons.
- branch:audio-get-recording-size => Add the ability to check recording size to avoid recording_data.size() == 0 error
- branch:3.2-monkey-fix-linux => All 3 audio fixes of the above.

##### Versions

We took the decision to use gemstones names in alphabetical order for versions

For now only Amethyst exists and we don't really know what will force us to change it (Godot 4.0?)

Here is a quick overview of versions

Amethyst:
- merge planemesh2d
- merge tiledata-swap
- merge audio-fix-get-recording-cowdata
- merge audio-get-recording-size
- merge 3.2-monkey-fix-linux-clean

## Godot Engine

Original repository: https://github.com/godotengine/godot

Homepage: https://godotengine.org