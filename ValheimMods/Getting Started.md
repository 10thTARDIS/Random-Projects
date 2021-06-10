[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges) 

*Currently working with:*  
[![valheim v0.154.1](https://img.shields.io/badge/Valheim-v0.154.1-blue)](https://www.valheimgame.com/) [![valheim plus v0.9.8.2](https://img.shields.io/badge/Valheim%20Plus-v0.9.8.2-blue)](https://github.com/valheimPlus/ValheimPlus) [![WeylandMod v1.5.0](https://img.shields.io/badge/WeylandMod-v1.5.0-blue)](https://github.com/WeylandMod/WeylandMod)

---

# Introduction

I've read a lot of guides over the last week or two on how to get started with modding Valheim.  This guide is intended solely to help my small group of friends mod their game to play on our shared server, but the concepts in this guide should let you install and play with any other Valheim mods you want.  It'll get you up and running with [Valheim Plus](https://github.com/valheimPlus/ValheimPlus), one of the most popular Valheim mods at the moment, along with the [WeylandMod](https://github.com/WeylandMod/WeylandMod) pack, which we selected to share our maps over the Valheim Plus shared maps due to its ability to hold a copy of the shared map on the server.  Since our friends aren't always online at the same time, this makes sure we all get to benefit from map sharing.  Both Valheim Plus and WeylandMod are under active development, which I'm hoping will mean that they will either continue working after a Valheim update, or will rapidly be updated to allow them to work.

Further note, this is how you mod the client side.  After building and tearing down a couple of servers as I learned, I ended up deciding that the $10 for a license to [AMP](https://cubecoders.com/AMP) was worth it, and bought that.  Given this game is still in early and active development, I didn't want to commit too much time to something that could ending up breaking and requiring even *more* time to fix as new patches are released.  Valheim Plus is natively supported by AMP, with a minimal-click deploy option that gets Valheim Plus and its dependencies running, and installing the WeylandMod pack as they recommend on their repository was a matter of a few more moments.

# Install mod manager and the shared map mod
* Install r2modman
	* Go to [the download page](https://thunderstore.io/package/ebkr/r2modman/)
	* Select "Manual Download"
	* Extract the .zip folder, and run the exe to install.
* Launch r2modman, and select "Valheim" when asked what game you are modding.  When asked for which profile this should be for, select Default.
* Go to the Online tab in the sitebar, under Mods.  
	* Select the BepInExPack_Valheim listing, and click Download.
	* Find and select the WeylandMod pack, and Download the mod and its dependencies.
	* Find and select ValheimPlus, and Download the mod and its dependancies.

Congratulations, you should now have all the mods you need installed.  To start playing the modded game, select "Start modded" in r2modman.  If you want to play without mods (note: **you cannot play unmodded on a modded server**, and moving a character from a modded server to an unmodded **will cause you to lose items** due to inventory slot mismatches), select "Start vanilla," or start Valheim in Steam.

# Updating Mods

To update the mods, open r2modman, go to Settings, and scroll down to the bottom option, "Update all mods."  That should update Valheim Plus, WeylandMod pack, and any other mods installed through r2modman.

Congratulations, you should now be fully up-to-date.

# Other Recommended Mods and Apps

This is where I'll list out recommended mods and applications for Valheim.

* Back up your character files automatically with [Valheim Save Shield](https://github.com/Razzmatazzz/ValheimSaveShield/releases).  I've lost items after a server issue before, and when switching between modded and unmodded servers, and this would have saved me some trouble.
