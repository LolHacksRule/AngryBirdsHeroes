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
  * Dumping of all game data.
* dnSpy
  * Decompiler for C# assemblies.
* de4dot
  * Minor deobfuscation of two assemblies.
* IlSpy
  * Decompiler that tends to work better with deobfuscated assemblies when dnSpy doesn't.
* JetBrains dotPeek
  * Decompiler that tends to work better with assemblies when dnSpy or IlSpy doesn't.

## Why did you consider this project?

I enjoyed AB Epic as a kid. I wanted a PC release like www.github.com/BP-Innovation/Bad-Piggies-Original did with Bad Piggies, and wanted to get an idea of figuring out the balancing data format.

## Why this name?

Angry Birds Heroes sounds like it fits for such a project, supposedly the internal name of the game.

## How do I contribute?

A: Contact me on Discord or Twitter.
