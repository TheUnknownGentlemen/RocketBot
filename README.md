# RocketBot

## Official discord channel for user and developer discussions.
* https://discord.gg/y6EU2qY

## Window
![alt tag](https://raw.githubusercontent.com/TheUnknownGentlemen/RocketBot/master/Main.jpg)  
![alt tag](https://raw.githubusercontent.com/TheUnknownGentlemen/RocketBot/master/Settings.jpg)


A Pokémon Go bot in C#

## Features
* PTC / Google Login (Google Login is currently unavailable due to API incompatibility)
* Get Map Objects and Inventory
* Live map showing Pokéstops, Gyms, Pokemon and farming path
* Farm Pokéstops
* Farm all Pokémon in the neighbourhood
* Auto-Recycle uneeded items while keeping wanted items
* View all Pokémon CP/IV %
* Transfer/Powerup/Evolve Pokémon
* Output level and needed XP for levelup
* Output Username, Level, Stardust, XP/hour, Pokémon/hour
* Automatic use of Razzberries (currently unavailable due to API incompatibility)

## Getting Started
### Download
Download the bot from the [release](https://github.com/TheUnknownGentlemen/RocketBot/releases) tab.
Or clone the repository and compile it yourself for the newest bugfixes and improvements.
### Settings
Change your settings using the settings dialog on the bot.
### Wola
Click Login and enjoy!

# Settings

## DefaultLatitude
* *12.345678* - Latitude of your location you want to use the bot in. Number between -90 and +90. Doesn't matter how many numbers stand after the comma.

## DefaultLongitude
* *123.456789* - Longitude of your location you want to use the bot in. Number between -180 and +180. Doesn't matter how many numbers stand after the comma.

## DefaultAltitude
* *123.456789* - Altitute of your location you want to use the bot in. Set it to something beween 9 and 10 for most locations.

## AuthType
* *Google* - Google login
* *Ptc* - Pokémon Trainer Club

## Username
* *username* - Your username or google mail.

## Password
* *password* - Your password. It is stored in plain text, so make sure your computer is save.

## TransferType
Favorited Pokemon are never transfered!
* *none* - disables transferring
* *cp* - transfers all Pokémon below the CP threshold
* *duplicate* - Only keeps the one Pokemon of each type with the highest CP.
* *IVDuplicate* - Only keeps the one Pokemon of each type with the highest IV.
* *IVDuplicateUnderCPThreshold* - Only keeps the one Pokemon of each type with the highest IV and keeps all Pokemon above the IV and CP threshold. - Recomended
* *all* - transfers all Pokémon

## Do not transfer Pokemon above CP
* *CP* - Pokemon above this value will not be transfered.

## Do not transfer Pokemon above IV
* *IV* - Pokemon above this value will not be transfered.

## Use razzberry when Pokemon is above CP
* *CP* - When you encounter a Pokemon above this value a razzberry will be used.

## Use razzberry when catch probability is below
* *probability* - When you encounter a Pokemon below this value a razzberry will be used.

## Minimum TravelSpeed
* *Speed* - Minimum Travel speed in km/h. Each time you move somewhere your speed is randomized between min and max.

## Maximum TravelSpeed
* *Speed* - Maximum Travel speed in km/h

## Auto Inventory management
* *yes/no* Enables or disables automatic inventory management. Whenever you have only 10 item slots left, items will be recycled so you have 30 item slots left.
           First potions (from worst to best) are recycled, then berries (also those berries that are not implemented yet), then Revive (first Revive, then max Revive), then Pokeballs (from worst to best).
		   This makes sure that you always have the minimum number of items specified and the best for each category.

## Minimum number of Revive
* *number* Auto Inventory management will keep at least this number of Revive/max Revive

## Minimum number of Pokeballs
* *number* Auto Inventory management will keep at least this number of Pokeballs/Great Balls/Ultra Balls/Master Balls

## Minimum number of Potions
* *number* Auto Inventory management will keep at least this number of Potion/Super Potion/Hyper Potion/Max Potion

## Minimum number of Berries
* *number* Auto Inventory management will keep at least this number of Razzberry/Blukberry/Nanaberry/Pinapberry/Weparberry
