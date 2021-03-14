# Introduction

I've read a lot of guides over the last week or two on how to get started with modding Valheim.  This guide is intended solely to help my small group of friends mod their game to play on our shared server, but the concepts in this guide should let you install and play with any other Valheim mods you want.  It'll get you up and running with [Valheim Plus](https://github.com/valheimPlus/ValheimPlus), one of the most popular Valheim mods at the moment, along with the [WeylandMod](https://github.com/WeylandMod/WeylandMod) pack, which we selected to share our maps over the Valheim Plus shared maps due to its ability to hold a copy of the shared map on the server.  Since our friends aren't always online at the same time, this makes sure we all get to benefit from map sharing.

Further note, this is how you mod the client side.  After building and tearing down a couple of servers as I learned, I ended up deciding that the $10 for a license to [AMP](https://cubecoders.com/AMP) was worth it, and bought that.  Given this game is still in early and active development, I didn't want to commit too much time to something that could ending up breaking and requiring even *more* time to fix as new patches are released.  Valheim Plus is natively supported by AMP, with a minimal-click deploy option that gets Valheim Plus and its dependencies running, and installing the WeylandMod pack as they recommend on their repository was a matter of a few more moments.

# Install mod manager and the shared map mod
* Install r2modman
	* Go to [the download page](https://thunderstore.io/package/ebkr/r2modman/)
	* Select "Manual Download"
	* Extract the .zip folder, and run the exe to install.
* Launch r2modman, and select "Valheim" when asked what game you are modding.  When asked for which profile this should be for, select Default.
* Go to the Online tab in the sitebar, under Mods.  
	* Select the BepInExPack_Valheim listing, and click Download.
	* Find and select the WeylandMod pack, and Download the mod.

# Add Valheim Plus to r2modman

By this point, you will have the shared map mod installed, but you also need to have Valheim Plus installed to connect to our server.  Installing Valheim Plus in the usual fashion doesn't actually allow you to launch the game with other mods from r2modman, so we need to add it to the mod manager.  Luckily, this is pretty easy.

* From this Github repo, download this .zip file: https://github.com/10thTARDIS/Random-Projects/raw/main/ValheimMods/ValheimPlusFiles.zip.  
	* Extract them to a place of your choosing where you can find them again (like your desktop or your downloads folder).
* Go back to r2modman, and go to Settings.
	* In Settings, click "Browse data folder".  This should open an Explorer window.
	* Click "Valheim" -> "profiles" -> "Default" -> "BepInEx" to navigate to where the plugins are stored.
	* Open another Explorer window to the place you saved the files for Valheim Plus.  There should be two files there, valheim_plus.cfg and ValheimPlus.dll.  Move the valheim_plus.cfg file to the BepInEx "config" folder, and the ValheimPlus.dll file to the BepInEx "plugins" folder. 

Congratulations, you should now have an installed version of Valheim Plus.  To start playing the modded game, select "Start modded" in r2modman.  If you want to play without mods (note: you cannot play unmodded on a modded server), select "Start vanilla," or start Valheim in Steam.
