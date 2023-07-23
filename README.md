# Alucard Release Page

This is the official release page for the Alucard mod. Head over to the releases page to download! For more information, visit [https://csharpm7.github.io/Alucard/](https://csharpm7.github.io/Alucard/)
For the Richter Redirect companion mod, visit 

## Prerequisit Plugins 

Alongside Arcorpolis, you will need the following plugins:
- [nro_hook](https://github.com/ultimate-research/nro-hook-plugin/releases)
- [smashline_hook](https://github.com/blu-dev/smashline_hook/releases)


## Installation

Unzip the contents of the latest release, and drag directly to the root of your SD card! If done properly, you should see 3 Alucard-related folders inside `ultimate/mods/`. **Make sure you do not rename any of these folders.** This will also add a few other folders that are used to keep track of the current version of Alucard. Whenever a new release is published here, you should receive a notification about a new Alucard update the next time you boot smash with Alucard enabled.

When booting Smash for the first time with these mods, make sure you chose NOT to enable all new mods! **Moveset and Moveset X will cause crashes if both are enabled.**

## Folders

**alucard**: The main folder the contains various parameters, as well as all the models and animations for Alucard. Do not alter this folder

**alucard moveset**: This is the base moveset for alucard, optimal for base-game smash.

**alucard moveset x**: For overhaul packs, as well as a handful of custom fighters, Alucard's original moveset will force crashes due to how skyline works at the moment. To compensate, this lighter version of the moveset (featuring Mist Dash) will be compatible with a heavily modified version of smash

**hdr - alucard**: This contains a `motion_patch.yaml` file that is essential to Alucard's compatibility with HDR. Create a copy of your current `hdr` folder, and copy all of the contents **except for the richter folder** into this folder. This folder won't get updated via the hdr-launcher, so make sure you manually update this every once in a while.

## Gameplay Mod Compatibility

Currently, this mod somewhat supports other gameplay mods being ran concurrently, though you will most likely need to use Moveset X. For large overhaul packs, you'll want to make sure you have their stage mods enabled. You'll also need to iron out any conflicts (such as motion_list.bin and animation files), I recommend making copies of the mod folders. Not every moveset mod is compatible with Alucard; there is no list of these movesets and I cannot do anything about that.
