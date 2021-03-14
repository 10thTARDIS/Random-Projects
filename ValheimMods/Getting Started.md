* Install r2modman
	* Go to [the download page](https://thunderstore.io/package/ebkr/r2modman/)
	* Select "Manual Download"
	* Extract the .zip folder, and run the exe to install.
* Launch r2modman, and select "Valheim" when asked what game you are modding.  When asked for which profile this should be for, select Default.
* Go to the Online tab in the sitebar, under Mods.  
	* Select the BepInExPack_Valheim listing, and click Download.
	* Find and select the WeylandMod pack, and Download the mod.
By this point, you will have the shared map mod installed, but you also need to have Valheim Plus installed to connect to the server.  Let's add that to r2modman now:
* From this Github repo, download this .zip file: https://github.com/10thTARDIS/Random-Projects/raw/main/ValheimMods/ValheimPlusFiles.zip.  
	* Extract them to a place of your choosing where you can find them again (like your desktop or your downloads folder).
* Go back to r2modman, and go to Settings.
	* In Settings, click "Browse data folder".  This should open an Explorer window.
	* Click "Valheim" -> "profiles" -> "Default" -> "BepInEx" to navigate to where the plugins are stored.
	* Open another Explorer window to the place you saved the files for Valheim Plus.  There should be two files there, valheim_plus.cfg and ValheimPlus.dll.  Move the valheim_plus.cfg file to the BepInEx "config" folder, and the ValheimPlus.dll file to the BepInEx "plugins" folder. 
Congratulations, you should now have an installed version of Valheim Plus.  To start playing the modded game, select "Start modded" in r2modman.  If you want to play without mods (note: you cannot play unmodded on a modded server), select "Start vanilla," or start Valheim in Steam.
