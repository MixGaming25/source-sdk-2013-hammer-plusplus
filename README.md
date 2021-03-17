# source-sdk-2013-hammer-plusplus
A new version of hammer for source sdk
--- Install instructions ---
This build of Hammer++ only works when started inside Half Life 2's or Source SDK 2013 Singleplayer's directory!

1. Find where Half Life 2 or Source SDK 2013 Singleplayer is installed

2. Copy over everything inside this download's "bin" folder into HL2's/SDK 2013's "bin" folder.
	Your paths should look like this:
	<steam install location>/steamapps/common/half life 2/bin/hammerplusplus.exe
	<steam install location>/steamapps/common/half life 2/bin/hammerplusplus/<other files>
	or
	<steam install location>/steamapps/common/source sdk base 2013 singleplayer/bin/hammerplusplus.exe
	<steam install location>/steamapps/common/source sdk base 2013 singleplayer/bin/hammerplusplus/<other files>
	
3. Add hammerplusplus.fgd in Hammer++'s game configuration

- If you do not add the FGD file, you will be missing the following features:
-- Particle rendering
-- Particle browser
-- Editor-only 3D world text

4. (Mapbase/Sourcemods only) the -game parameter is not required as it's automatically added
	This means you don't need to do the shortcut method anymore, simply start the hammerplusplus.exe
	
--- Other Information ---
Hammer++ does not use the GameConfig.txt, instead it uses its own GameConfig.txt located in the hammerplusplus sub folder. 
If not found, it copies the normal game configuration.
Keep this in mind when following any tutorials.

--- Uninstallation ---
To uninstall, simply delete the hammerplusplus.exe
You can also optionally delete the hammerplusplus folder, but this will remove all saved settings for Hammer++.
