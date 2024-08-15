# Chargen
Random Character Generator

I originally created this file to prompt for a personal writing challenge, so it is far from perfect (see "Known Bugs").  At the suggestion of others, I have put this file up on GitHub so others can check it out.  Just be nice, don't steal it and call it your own.  I do not own the text referenced below, only the code.

This file uses Javascript to generate a listing of 1000 characters based on the tables in the sources below.  Race/Class/Level/Gender/Alignment probability is based off 1-100 and assigned from there.

This file is a self contained random character generator.  It uses the following sources to generate names.
Dragon Magazine "By Any Other Name" series (Wizards of the Coast)
* Issue #251: Elves
* Issue #261: Dwarves
* Issue #262: Gnomes and Halflings
* Issue #267: Drow
* Annual #5: Sages, Shops, Smithies, and Taverns (Businesses)
* Issue #281: Derro, Duergar, Kuo-Toa, Mind Flayers, and Svirfneblin (Races of the Underdark)
For classes and levels:
* Dungeons & Dragons Dungeon Master Guide 3.0 - Wizards of the Coast
* Dungeons & Dragons Dungeon Master Guide 3.5 - Wizards of the Coast
* Pathfinder GameMastery Guide - Paizo Publishing
* Pathfinder for Savage Worlds - Pinancle Entertertainment Group

Known Bugs
* If the same class is generated twice, it will not total up the classes (ex, Commoner 4 / Commoner 1 will not display as Commoner 5)
* It does not take into consideration Alignment to Class or Race.
