### update
this is a very clunky proof-of-concept project. please see the more refined updated version inspired by this:
https://github.com/sheysyn/NFS_UGs_and_MW_clutch_trainer



# NFSU2Clutch
 Manual Clutch trainer mod for Need for speed underground 2

[https://youtu.be/Twt7HC5NpSg](https://youtu.be/Twt7HC5NpSg)

# Instructions
 - Download the repo (Green "Code" button. Download as zip)
 - Extract with 7zip/WinRAR etc
 - Open the game. Open a race/freerun
 - Open the .CT file (its just a CheatEngine Project)
 - Select the game from Processes tab (top left glowing box)
 - Click initialize/reset button on the little window
 - if console looks ok, Try pressing "K","J" and "N"
 - if no weird errors:
 - "K - Clutch", "J - Gear Up", "N - Gear Down"
 - "K" needs to be pressed down while gear change keys are about to be pressed(otherwise it wont accept).
 - You can still use the game's default gear changer buttons.

(the key "K" is probably overlapping with your BackCamera keybinding. Change it from main menu>options>controls or someshit)

# How does it work?
Activating clutch basically shifts your gear to "(N)eutral" while you can still change gears at the background. Releasing the clutch shifts back to whatever you moved your gear to.

examples:
what keys are pressed : (gear 2) : K press -> J, J -> K release (gear 4)
what happens : (gear 2) -> (gear N) -> (gear 4)

# technicality
are you going to be able to rev your engine with clutch and increase tracktion in times of need? no. again, you dont actually clutch. you switch gears so rpm boosting type things won't happen.

# Code
In CE top menu: Table > Show Cheat Table Lua Script
Clutch engagement is checked every 100ms. you can tweak that value by editing the lua script and saving Ctrl+S. (I recommend restarting the trainer after this.)

# Notes
this is my first time using Cheat Engine for something that is not baby stuff. the ui is shit, all variables are hardcoded etc. let me know your problems in issues tab of github

https://github.com/clod44/NFSU2Clutch


--

credit me in your inspirations


