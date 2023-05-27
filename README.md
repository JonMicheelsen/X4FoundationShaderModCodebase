# X4FoundationShaderModCodebase
Various rendering experiments for X4 Foundation. Code part.

NOTE! This mod is still very much WIP!!
NOTE!! This mods assumes you to already be playing on Ultra, since it for now adds more work for the gpu to do.

How to install:
Download by clicking the green "Code" button and select the "Download Zip" button.
Go to your root X4 Foundation install folder. In Steam you can right click the game icon and under "Manage" you can select "Browse local files" to find the root install folder. In here make a new folder with the name "shadergl"
Open the ZIP file. In it you find the autogenerated "X4FoundationShaderModCodebase" folder, and in that folder you find the "shaders" folder. Put the "shaders" folder with all content in it directly in the  "shadergl" folder. So to rephrase .../X4 Foundation/shadergl/shaders/...
Add "-prefersinglefiles"  without the quotation marks to the games launch directives. In Steam you right click the game in your library go to "Properties..." and in "General" you find "Launch Options". If you run the X4_nonsteam.exe version the easiest way is to make a shortcut the exe, right click it, go to "Properties" and after the last quotation mark in the "Target:" path found in the "Shortcut" tab you add the "-prefersinglefiles"  without the quotation marks.

Alternatively, if you are already familiar with using git, and have for instance GitHubDesktop installed you can check out the project mapped directly to the "shadergl" folder and just get updates on the fly, I try to push whenever I have finished part of a feature I'm working on, sometimes several times a day. Don't forget "-prefersinglefiles". I highly recommend this instead of the above!

I don't like feature "x"!?
If you want to play around with the settings, all the features are exposed in: "jon_mod_defines.h" found in the "shaders" folder. Note some things in there may be temp and not do anything or not work if other things are not running, so play around with it at your own peril. :D


