# skript-utility
A couple of useful commands &amp; functions for skript


## Files
- `main.sk` - This is the main file that contains the core commands and only requires [Skript](https://github.com/SkriptLang/Skript).
- `skbee.sk` - This file contains tweaks that require [SkBee](https://github.com/ShaneBeee/SkBee) to work.

## Commands
`/command <required> [optional]`

 Command | Permission | Description
 :--:|:--:|:--
 /heal `<player>` `[amount]` | fireutil.heal | Heals the specified player. Defaults to 10 hearts.
 /feed `<player>` `[amount]` | fireutil.feed | Feeds the specified player. Defaults to 10 points.
 /stun `<player>` `<duration (sec)>` | fireutil.stun | Grants all immobilizing effects for the specified duration.
 /broadcast `<message>` | fireutil.broadcast | Sends the message to all players. Supports Legacy Color Codes and Hex Codes in the format `<#ff0000>`.
 /send `<player>` `<message>` | fireutil.send | Sends the message to a specific player. Supports Legacy Color Codes and Hex Codes in the format `<#ff0000>`. 
 /yeet `<player>` | fireutil.yeet | Sends a player into outer space.
 /enderchest | fireutil.enderchest | Opens a player's ender chest.
 /crafting | fireutil.crafting | Opens the Crafting Table GUI for the player.
 /invsee `<player>` | fireutil.invsee<br>fireutil.invedit | Opens another player's inventory.
 /endersee `<player>` | fireutil.endersee<br>fireutil.enderedit | Opens another player's enderchest.
 /rename `<text>` | fireutil.rename | Renames the held item. Supports Legacy Color Codes and Hex Codes in the format `<#ff0000>`.
 /stack `[number]` | fireutil.stack | Sets the item count of the held item. Defaults to 64 items.
 /eval `<string>` | fireutil.eval | *Parses input as skript effect.
 
 \* Requires SkBee
 
 More coming soon:tm:
