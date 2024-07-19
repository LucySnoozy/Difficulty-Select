# Difficulty-Select
Difficulty Select Mirror

This mod changes the difficulty of the game.
Each area in Elden Ring has it's own scaling which changes all defenses and resistances of enemies, the damage dealt by them and their max HP and stamina. Each of these values will be multiplied, depending on what scaling you choose (e.g. 130% = x1.3).

Note: Specific enemy base values are not changed!

Available scaling options:
50%-90%
110%-200%
250%
300%



Installation:

- Download ModEngine2﻿ and extract the .zip file to anywhere you like (preferably not in the Desktop/Download folder. On another driver or inside the game folder works just fine)

- Download this mod, open the .zip file, go into the scaling folder of your choosing and drag out the map and msg folders and the regulation.bin into your ModEngine2's mod folder.

- Start the game with launchmod_eldenring.bat and enjoy a different difficulty.

With Seamless:

- Do the previous installation steps first.
- Download the lastest version of Seamless Coop﻿ and install it as instructed there.
- Go into the Seamless Coop folder that is located in \steamapps\common\ELDEN RING\Game and mark these four files:

"crashpad, locale, ersc.dll, ersc_settings.ini"


- ﻿After marking them, press ctrl + c

- Go into the folder where Mod Engine 2 is located. You can find launchmod_eldenring.bat in the same folder.
- Press ctrl + v to paste the copied files into that folder.
- Now open config_eldenring.toml with notepad/notepad++, mark the whole Line 14 and replace it with this:

  *external_dlls = ["ersc.dll"]*

Now you have installed Seamless Coop with Difficulty Select. Simply use launchmod_eldenring.bat to start the game with both.
If it doesn't start right away you might have to change modengine2_launcher.exe and eldenring.exe to start as Administrator in the Compatibility Tab in their Properties.

Have fun!
(NOTE: Every player needs the same mod files for Seamless AND Difficulty Select.)



Compatibility:

To make this mod compatible with mods that edit the regulation.bin, you have to merge them. Download the provided .csv and import them into "SpEffectParam" using DSMapStudio.

Thanks to Dalvik for wording suggestions!

If you would like to support me financially you can do so on Ko-fi﻿ (https://ko-fi.com/lucysnoozy)! Any support is greatly appriciated but obviously not necessary to enjoy my mod.
