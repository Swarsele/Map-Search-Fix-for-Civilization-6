~~Map Search Fix by Swarsele

Description of the aforementioned bug can be found here:
https://forums.civfanatics.com/threads/1-0-0-341-map-search-stuck.656149/

As the game seems to perform well when started with all mods unloaded, my solution 
is to simply run a small .bat file every time before starting the game. This .bat file then
copies a "clean" mods.sqlite file into the "My Games\Sid Meier's Civilization 6" folder,
and Map Search should work.

====================================================================================
STEPS TO FIX:
-In "Enable Civ 6 Mods.bat", change the first argument to the destination of your 
clean mods.sqlite
-Also, change the second argument to point to your "My Games\Sid Meier's Civilization 6" 
Folder

In order for MapSearch to work, run "Enable Civ 6 Mods.bat" each time before 
starting the game.
The "Original Cache Files" should not be needed, but you can try putting them 
into "My Games\Sid Meier's Civilization 6" if you encounter problems.

====================================================================================

CREATING A "CLEAN" MODS.sqlite:
-start by deleting the cache and ModUserData from the "My Games\Sid Meier's Civilization 6"
directory.
-start the Game normally, disable all mods, and start a game.
-exit Civilization 6 once the game has loaded.
-now, go to "My Games\Sid Meier's Civilization 6" and make a backup of mods.sqlite
-you can also make a backup of the Cache and ModUserData Folders if you want (might
not be needed however)

If you find a more elegant solution to this problem, do not hesitate to contact me at
nautilus.dw@gmail.com

All the best