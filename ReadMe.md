Version 1.0 of my Saving mod for Muck

This version currently only saves the player, no world objects, npcs etc yet, as well as no unlocks for now.

What this saves exactly

Inventory, including armor and arrows
Powerups
Stats
Worldseed

How it works

----The save file will be located at the same place the game stores it's log file-----
        ---C:\Users\YOURCOMPUTERSUSERNAME\AppData\LocalLow\Dani\Muck----

Upon loading in the first time if there is no save file already it will create a "Dummy" file for convenience in code and as a guide/reference for anyone looking at the file. If a save already exists it will load everything from it and do what is needed to setup the player accordingly.

Upon pausing and pushing the "Leave Game" button it will save all the currntly saved info to a new player file. It will take the existing save file, which will be the blank "Dummy" file if you have never saved before, and it will add "Backup" to the file name. 
If for some reason you corrupt your save you can rename the backup.

