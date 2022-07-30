# DC2
Dark Cloud 2 is one of my favorite video games. 
This excel file is used to optimize the weapon leveling used in the game as well as understanding other mechanics that are in the game.

As this is a fairly old game, released in 2003, I have uploaded this to show part of my knowledge and passion, instead of for universal use. As such I will not talk in detail about the usage but what features I made use of in creating this project.
For user entry in this complicated layout, the critical cells to customize what you need are bordered in by thick lines on all sides, and thin line borders denote useful sections of the page without the need to edit anything.

To make this project work, I got a table of maximum and base stats for each weapon in the game. This table is refered to in the "Weapon Synth Calculator" sheet through VLOOKUP and to operate a dropdown cell for selecting which weapon to use.
After pulling in the necessary information, the sheet uses deterministic math to optimize what stat points to apply to the second weapon to effectively increase the main weapon stats. This process is constrained to only yield possible results because of the limitations of the second weapon's max stats and the amount of stats that both weapons can increase. 
The calculation is complete with a heat map coloring scheme for what stats will increase the most, as well as outputting the final stats if the weapon was upgraded in this way.

Other sheets are for understanding the leveling system in the game, such as how much experience each dungeon would give and how much experience each weapon needs to increase.
