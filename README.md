# AngryBirdsHeroes

This is an experimental decompilation of Angry Birds Epic into a Unity project for building on other platforms, preferably Windows.

## What version?

v1.57 (Android, Google Play, likely similar for iOS/WinPhone8). Versions beyond use il2cpp which is a mess to go through (besides getting this done would help a lot with it from reusing similar assets). It may likely be possible to do older versions.

## Is any original source code used?

No, Rovio Entertainment Ltd/Chimera Entertainment GmbH has the original source code to the game's Unity project and both companies' proprietary libraries while me and contributors do NOT have access to it and will NOT plan to use if so. Best we can use is decompiled C# scripts.

## A lot of materials don't work!

The game's materials uses proprietary shaders from the second said company and decompiling them isn't something the Unity engine likes.

## What tools were used?

* uTinyRipper 
  * Dumping of all game data as the base project.
* dnSpy
  * Decompiler for C# assemblies.
* de4dot
  * Minor deobfuscation of two assemblies.
* IlSpy
  * Decompiler that tends to work better with deobfuscated assemblies when dnSpy doesn't.
* JetBrains dotPeek
  * Decompiler that tends to work better with assemblies when dnSpy or IlSpy doesn't.

## How's it going?

* Text Assets (100%)
* Resources (100%
* Scripts (45%)
* Materials (14%)
* Fonts (100%)
* Meshes (100%)
* Textures (100%)
* Shaders (45%)

## Why did you consider this project?

I enjoyed AB Epic as a kid. I wanted a PC release like www.github.com/BP-Innovation/Bad-Piggies-Original did with Bad Piggies, and wanted to get an idea of figuring out the balancing data format.

## Why this name?

Angry Birds Heroes sounds like it fits for such a project, supposedly the internal name of the game.

## How do I contribute?

Contact me on Discord or Twitter for whatever you want to contribute for, I will credit you for doing so.
