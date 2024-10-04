# Nalamanar's Choice Modlist #

## Requirements ##

* Skyrim SE GOG 1.6.1179
* Latest Microsoft Visual C++ Redistributable for Visual Studio 2022 x64
* Latest Microsoft Visual C++ Redistributable for Visual Studio 2022 x86

## Best Practices ##

* A clean install of Skyrim
* A new character

## Installation ##

* First install the requirements under "Before you start"
* Run the game once to set initial graphics settings
* Download Wabbajack (https://www.wabbajack.org/) and install it
* Download "Nalamanars_Choice.wabbajack" under the latest release
* Run Wabbajack and select install from disk
* Find the .wabbajack file you downloaded above
* Select an installation directory that's outside the Skyrim game directory and Wabbajack install directory

## INI Configuration ##

* Download Bethini Pie from Nexus (https://www.nexusmods.com/site/mods/631)
* Install Bethini Pie wherever you wish; I install it in a Mod Tools folder at the top level of the C drive
* Run Bethini Pie
* Select Skyrim Special Edition
* Select the graphics setting which the game determined at launch
* Apply the recommended tweaks
* Enable grass fade in under Environment
* Double check the improved snow shader is turned off under Environment
* Save and exit

## Running the Game ##

* Go the installation directory you created when installing the .wabbajack file
* Run the Mod Organizer 2 executable
* Make sure the dropdown in the upper right corner next to "Run" has SKSE64 selected
* Click Run
* Enjoy the game!

## Alternate Start Recommendations ##

Some of the alternate starts work better than others with an unleveled world, especially if you don't already know the game and how to get out of certain situations. I don't cover starts exclusive to non-Khajiits because this is designed for a Khajiit playthrough.

### Recommended ###
* **Camping in the woods**: If you just want to skip the opening sequence, start in the same area as vanilla, and have the dragon quest already started, this is the best start. You'll get a free place to sleep and a good selection of low level starting equipment as well.
* **Caught crossing the border illegally**: This is the vanilla start, and should be fine but you'll have to playthrough the vanilla opening sequence.
* **Khajiit caravan guard**: This could fun, though I noticed the Khajiit Has Wares mod didn't load in properly with this start. More testing needed. Check out the shrine at the campsite though!

### Should Be Fine ###
* **Arrived by ship**: You'll have the option of the port side cities, which can have some light spoilers. I don't recommend Raven Rock because it is a high level area.
* **Property owner**: You'll get for a free something that's usually a significant early game upgrade, and with the inn mod you won't be as desperate for storage early game.
* **Member of a guild**: You'll miss out on finding the faction and figuring out how to join it, as well as the faction starting quest. But there's nothing wrong with this if you don't mind some mild spoilers and skipping some quest content.
* **Escape my cell**: You'll be in a dungeon, but with khajiit claws and stealth you should be fine. If you want fewer initial quests popping up, and want to just wander around and explore without dragons hanging over your head, this start is probably the best.
* **Patron at an inn**:  Most of these are okay, though some inns will start you off in higher level areas and none of them give you any real equipment. If you pick up quests there you may find them too high level for start. I'd avoid Nightgate, Old Hroldan Inn, The Retching Netch, and the Frozen Hearth. Avoid quests near the Moorside Inn and the Silver-Blood Inn.
* **Vigilant of Stendarr**: This drops you in a mid level zone, so be careful when approaching ruins/dungeons, but other than that you'll get Vigilant friends, some nifty starting equipment for a melee/restoration build, and a safe place to sleep and store items.
* **Shipwrecked off the coast**: This will drop you near a moderate level area, where you have to figure out where to go, and have with little equipment. But if you want a more challenging start, this could be fun. Be warned if you decide to add survival mods as this start becomes significantly more challenging.

### Not Recommended ###
* **Outlaw in the wilds**: You'll be grabbed by hold guards at the first opportunity and have to pay a bounty or spend time in jail. Also the start location is random so you could get anything from Whiterun to a high level area.
* **Soldier in the army**: The civil war questline is notoriously buggy, and this will make patrols from the opposite faction hostile. It potentially blocks story progression and faction access until you're higher level and will significantly increase difficulty until you get good enough to deal with the patrols.
* **Attacked and left for dead**: You could get dropped in many random spots, which could mean high level areas, with zero gear. I think this would be fun for a later playthrough, but for a first playthrough it would more likely be frustrating.
* **Vampire in a secluded lair**: You probably don't want to start with vampirism for a first playthrough, and this can also drop you in high level areas.
* **Warlock's Thrall**: You get minimal starting gear, could get dropped in a high level zone, and once you leave the cave things in there become hostile. Could be workable but is risky.

### Anything But This ###
* **Necromancer in a hidden lab**: You'll get dropped in a high level zone with minimal starting equipment, with a high level enemy right outside your door with no other exits, and it's a spoiler for a later game quest area. I strongly recommend picking anything else.

## Azurite Config Spell ##

If you're annoyed by config spells like I am, there's an easy way to remove it. Once you start up the game, use the Azurite Meditation power and configure the weather how you like. Afterwards, go to the console (opened with ~ by default). Type help azurite 0. This should get you a list of ids - look for the meditation power. Take its spell id and type player.removespell id. You can save this id somewhere for easy reference if you ever want it back and it should remain available for search with the help function.
