# Adventure Help

Adventure, derived from the Goblins Adventure cog by locastan.

## adventure rebirth (Slash Command)
 - Usage: `/adventure rebirth `

Resets your character level and increases your rebirths by 1.

## adventure negaverse (Slash Command)
 - Usage: `/adventure negaverse <offering> `
 - `offering:` (Required) …

This will send you to fight a nega-member!

## adventure loot (Slash Command)
 - Usage: `/adventure loot [box_type] [number] `
 - `box_type:` (Optional) …
 - `number:` (Optional) …

This opens one of your precious treasure chests.

## adventure convert (Slash Command)
 - Usage: `/adventure convert <box_rarity> [amount] `
 - `box_rarity:` (Required) …
 - `amount:` (Optional) …

Convert normal, rare or epic chests.

## adventure aleaderboard (Slash Command)
 - Usage: `/adventure aleaderboard [show_global] `
 - `show_global:` (Optional) …

Print the leaderboard.

## adventure scoreboard (Slash Command)
 - Usage: `/adventure scoreboard [show_global] `
 - `show_global:` (Optional) …

Print the scoreboard.

## adventure nvsb (Slash Command)
 - Usage: `/adventure nvsb [show_global] `
 - `show_global:` (Optional) …

Print the negaverse scoreboard.

## adventure wscoreboard (Slash Command)
 - Usage: `/adventure wscoreboard [show_global] `
 - `show_global:` (Optional) …

Print the weekly scoreboard.

## adventure heroclass (Slash Command)
 - Usage: `/adventure heroclass [class] [action] `
 - `class:` (Optional) …
 - `action:` (Optional) …

Allows you to select a class if you are level 10 or above.

## adventure pet
 - Usage: `[p]adventure pet `

[Ranger Class Only]

### adventure pet find (Slash Command)
 - Usage: `/adventure pet find `

[Ranger Class Only]

### adventure pet forage (Slash Command)
 - Usage: `/adventure pet forage `

Use your pet to forage for items!

### adventure pet free (Slash Command)
 - Usage: `/adventure pet free `

Free your pet :cry:

## adventure bless (Slash Command)
 - Usage: `/adventure bless `

[Cleric Class Only]

## adventure insight (Slash Command)
 - Usage: `/adventure insight `

[Psychic Class Only]

## adventure rage (Slash Command)
 - Usage: `/adventure rage `

[Berserker Class Only]

## adventure focus (Slash Command)
 - Usage: `/adventure focus `

[Wizard Class Only]

## adventure music (Slash Command)
 - Usage: `/adventure music `

[Bard Class Only]

## adventure forge (Slash Command)
 - Usage: `/adventure forge `

[Tinkerer Class Only]

## adventure skill (Slash Command)
 - Usage: `/adventure skill [skill] [amount] `
 - `skill:` (Optional) …
 - `amount:` (Optional) …

This allows you to spend skillpoints.

## adventure setinfo (Slash Command)
 - Usage: `/adventure setinfo [set_name] `
 - `set_name:` (Optional) …

Show set bonuses for the specified set.

## adventure stats (Slash Command)
 - Usage: `/adventure stats [user] `
 - `user:` (Optional) …

This draws up a character sheet of you or an optionally specified member.

## adventure unequip (Slash Command)
 - Usage: `/adventure unequip <item> `
 - `item:` (Required) …

This stashes a specified equipped item into your backpack.

## adventure equip (Slash Command)
 - Usage: `/adventure equip <item> `
 - `item:` (Required) …

This equips an item from your backpack.

## adventure backpack
 - Usage: `[p]adventure backpack `

This shows the contents of your backpack.

### adventure backpack show (Slash Command)
 - Usage: `/adventure backpack show [show_diff] [rarity] [slot] `
 - `show_diff:` (Optional) …
 - `rarity:` (Optional) …
 - `slot:` (Optional) …

This shows the contents of your backpack.

### adventure backpack equip (Slash Command)
 - Usage: `/adventure backpack equip <equip_item> `
 - `equip_item:` (Required) …

Equip an item from your backpack.

### adventure backpack eset (Slash Command)
 - Usage: `/adventure backpack eset <set_name> `
 - `set_name:` (Required) …

Equip all parts of a set that you own.

### adventure backpack disassemble (Slash Command)
 - Usage: `/adventure backpack disassemble <backpack_items> `
 - `backpack_items:` (Required) …

Disassemble items from your backpack.

### adventure backpack sellall (Slash Command)
 - Usage: `/adventure backpack sellall [rarity] [slot] `
 - `rarity:` (Optional) …
 - `slot:` (Optional) …

Sell all items in your backpack. Optionally specify rarity or slot.

### adventure backpack sell (Slash Command)
 - Usage: `/adventure backpack sell <item> `
 - `item:` (Required) …

Sell an item from your backpack.

### adventure backpack trade (Slash Command)
 - Usage: `/adventure backpack trade <buyer> <item> [asking] `
 - `buyer:` (Required) …
 - `item:` (Required) …
 - `asking:` (Optional) …

Trade an item from your backpack to another user.

## adventure start (Slash Command)
 - Usage: `/adventure start [challenge] `
 - `challenge:` (Optional) …

This will send you on an adventure!

# themeset
 - Usage: `[p]themeset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

[Admin] Modify themes.

## themeset add
 - Usage: `[p]themeset add `
 - Restricted to: `BOT_OWNER`

[Owner] Add/Update objects in the specified theme.

### themeset add pet
 - Usage: `[p]themeset add pet <pet_data> `

[Owner] Add/Update a pet object in the specified theme.<br/><br/>Usage: `[p]themeset add pet theme++name++bonus_multiplier++required_cha++crit_chance++always_crit`<br/><br/>`theme` is the one-word theme folder name. The default is `default`.<br/>`name` is the name of the pet.<br/>`bonus_multiplier` is a number between `1.00` and `2.00` for the reward bonus percentage on a successful adventure.<br/>`required_cha` is the required charisma/diplomacy level that the ranger must overcome to catch the pet - usually between `1` and `500`.<br/>`crit_chance` is the chance to have a critical strike, between `1` and `100` percent.<br/>`always_crit` is `True` or `False` for whether the pet will always have a critical strike when attacking.

### themeset add monster
 - Usage: `[p]themeset add monster <theme_data> `

[Owner] Add/Update a monster object in the specified theme.<br/><br/>Usage: `[p]themeset add monster theme++name++hp++dipl++pdef++mdef++cdef++boss++image`<br/><br/>`theme` is the one-word theme folder name. The default is `default`.<br/>`name` is the name of the monster.<br/>`hp` is the base amount of hp the monster has.<br/>`dipl` is the base amount of charisma/diplomacy the monster has.<br/>`pdef` is the percentage of physical resistance, `0.0` to `100.0`.<br/>`mdef` is the percentage of magic resistance, `0.0` to `100.0`.<br/>`cdef` is the percentage of charisma/diplomacy resistance, `0.0` to `100.0`.<br/>`boss` is whether the monster is a boss, determined with `True` or `False`.<br/>`image` is a URL for an image of the monster.

## themeset list
 - Usage: `[p]themeset list `
 - Aliases: `show`

[Admin] Show custom objects in the specified theme.

### themeset list monster
 - Usage: `[p]themeset list monster <theme> `

[Admin] Show monster objects in the specified theme.<br/><br/>The default theme is `default`.<br/>This will only display custom monsters added through the `themeset` command.

### themeset list pet
 - Usage: `[p]themeset list pet <theme> `

[Admin] Show pet objects in the specified theme.<br/><br/>The default theme is `default`.<br/>This will only display custom pets added through the `themeset` command.

## themeset delete
 - Usage: `[p]themeset delete `
 - Restricted to: `BOT_OWNER`
 - Aliases: `del, rem and remove`

[Owner] Remove objects in the specified theme.

### themeset delete monster
 - Usage: `[p]themeset delete monster <theme> <monster> `

[Owner] Remove a monster object in the specified theme.<br/><br/>The default theme is `default`.

### themeset delete pet
 - Usage: `[p]themeset delete pet <theme> <pet> `

[Owner] Remove a pet object in the specified theme.<br/><br/>The default theme is `default`.

# rebirth (Hybrid Command)
 - Usage: `[p]rebirth `
 - Slash Usage: `/rebirth `
 - Checks: `server_only`

Resets your character level and increases your rebirths by 1.

# negaverse (Hybrid Command)
 - Usage: `[p]negaverse <offering> `
 - Slash Usage: `/negaverse <offering> `
 - Aliases: `nv`
 - Cooldown: `1 per 3600.0 seconds`
 - Checks: `server_only`

This will send you to fight a nega-member!

# loot (Hybrid Command)
 - Usage: `[p]loot [box_type=None] [number=1] `
 - Slash Usage: `/loot [box_type=None] [number=1] `
 - Cooldown: `1 per 4.0 seconds`

This opens one of your precious treasure chests.<br/><br/>Use the box rarity type with the command: normal, rare, epic, legendary, ascended or set.

# convert (Hybrid Command)
 - Usage: `[p]convert <box_rarity> [amount=1] `
 - Slash Usage: `/convert <box_rarity> [amount=1] `
 - Cooldown: `1 per 4.0 seconds`

Convert normal, rare or epic chests.<br/><br/>Trade 25 normal chests for 1 rare chest.<br/>Trade 25 rare chests for 1 epic chest.<br/>Trade 25 epic chests for 1 legendary chest.

# loadout
 - Usage: `[p]loadout `
 - Aliases: `loadouts`

Set up gear sets or loadouts.

## loadout save
 - Usage: `[p]loadout save <name> `
 - Aliases: `update`

Save your current equipment as a loadout.

## loadout show
 - Usage: `[p]loadout show [name=None] `

Show saved loadouts.

## loadout delete
 - Usage: `[p]loadout delete <name> `
 - Aliases: `del, rem and remove`

Delete a saved loadout.

## loadout equip
 - Usage: `[p]loadout equip <name> `
 - Aliases: `load`
 - Cooldown: `1 per 600.0 seconds`

Equip a saved loadout.

# aleaderboard (Hybrid Command)
 - Usage: `[p]aleaderboard [show_global=False] `
 - Slash Usage: `/aleaderboard [show_global=False] `
 - Checks: `server_only`

Print the leaderboard.

# scoreboard (Hybrid Command)
 - Usage: `[p]scoreboard [show_global=False] `
 - Slash Usage: `/scoreboard [show_global=False] `
 - Checks: `server_only`

Print the scoreboard.

# nvsb (Hybrid Command)
 - Usage: `[p]nvsb [show_global=False] `
 - Slash Usage: `/nvsb [show_global=False] `
 - Checks: `server_only`

Print the negaverse scoreboard.

# wscoreboard (Hybrid Command)
 - Usage: `[p]wscoreboard [show_global=False] `
 - Slash Usage: `/wscoreboard [show_global=False] `
 - Checks: `server_only`

Print the weekly scoreboard.

# atransfer
 - Usage: `[p]atransfer `
 - Checks: `has_separated_economy`

Transfer currency between players/economies.

## atransfer give
 - Usage: `[p]atransfer give <amount> <players> `
 - Restricted to: `BOT_OWNER`

[Owner] Give gold to adventurers.

## atransfer withdraw
 - Usage: `[p]atransfer withdraw <amount> `
 - Cooldown: `1 per 600.0 seconds`
 - Checks: `server_only`

Convert gold to bank currency.

## atransfer deposit
 - Usage: `[p]atransfer deposit <amount> `
 - Checks: `server_only`

Convert bank currency to gold.

## atransfer player
 - Usage: `[p]atransfer player <amount> <player> `
 - Cooldown: `1 per 600.0 seconds`
 - Checks: `server_only`

Transfer gold to another player.

# mysets
 - Usage: `[p]mysets `

Show your sets.

# apayday
 - Usage: `[p]apayday `
 - Cooldown: `1 per 600.0 seconds`
 - Checks: `has_separated_economy`

Get some free gold.

# give
 - Usage: `[p]give `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

[Owner] Commands to add things to players' inventories.

## give loot
 - Usage: `[p]give loot <loot_type> [users=None] [number=1] `

[Owner] Give treasure chest(s) to all specified users.

## give item
 - Usage: `[p]give item <user> <item_name> <stats> `

[Owner] Adds a custom item to a specified member.<br/><br/>Item names containing spaces must be enclosed in double quotes. `[p]give item @locastan<br/>"fine dagger" 1 att 1 charisma rare twohanded` will give a two handed .fine_dagger with 1<br/>attack and 1 charisma to locastan. if a stat is not specified it will default to 0, order<br/>does not matter.<br/>available stats are:<br/> - `attack` or `att`<br/> - `charisma` or `diplo`<br/> - `charisma` or `cha`<br/> - `intelligence` or `int`<br/> - `dexterity` or `dex`<br/> - `luck`<br/> - `rarity` (one of normal, rare, epic, legendary, set, forged, or event)<br/> - `degrade` (Set to -1 to never degrade on rebirths)<br/> - `level` (lvl)<br/> - `slot` (one of `head`, `neck`, `chest`, `gloves`, `belt`, `legs`, `boots`, `left`, `right`<br/> `ring`, `charm`, `twohanded`)<br/><br/>`[p]give item @locastan "fine dagger" 1 att 1 charisma -1 degrade 100 level rare twohanded`

# devcooldown
 - Usage: `[p]devcooldown `
 - Restricted to: `BOT_OWNER`

[Dev] Resets the after-adventure cooldown in this server.

# makecart
 - Usage: `[p]makecart [stockcount=None] `
 - Restricted to: `BOT_OWNER`

[Dev] Force a cart to appear.

# genitems
 - Usage: `[p]genitems <rarity> <slot> [num=1] `
 - Restricted to: `BOT_OWNER`

[Dev] Generate random items.

# copyuser
 - Usage: `[p]copyuser <user_id> `
 - Restricted to: `BOT_OWNER`

[Owner] Copy another members data to yourself.<br/><br/>Note this overrides your current data.

# devrebirth
 - Usage: `[p]devrebirth [rebirth_level=1] [character_level=1] [users=None] `
 - Restricted to: `BOT_OWNER`

[Dev] Set multiple users rebirths and level.

# devreset
 - Usage: `[p]devreset <users> `
 - Restricted to: `BOT_OWNER`

[Dev] Reset the skill cooldown for multiple users.

# adventurestats
 - Usage: `[p]adventurestats `
 - Restricted to: `BOT_OWNER`

[Owner] Show all current adventures.

# heroclass (Hybrid Command)
 - Usage: `[p]heroclass [clz=None] [action=None] `
 - Slash Usage: `/heroclass [clz=None] [action=None] `
 - Cooldown: `1 per 7200.0 seconds`

Allows you to select a class if you are level 10 or above.<br/><br/>For information on class use: `[p]heroclass classname info`.

# pet (Hybrid Command)
 - Usage: `[p]pet `
 - Slash Usage: `/pet `
 - Cooldown: `1 per 5.0 seconds`

[Ranger Class Only]<br/><br/>This allows a Ranger to tame or set free a pet or send it foraging.

## pet free (Hybrid Command)
 - Usage: `[p]pet free `
 - Slash Usage: `/pet free `

Free your pet :cry:

## pet forage (Hybrid Command)
 - Usage: `[p]pet forage `
 - Slash Usage: `/pet forage `

Use your pet to forage for items!

# bless (Hybrid Command)
 - Usage: `[p]bless `
 - Slash Usage: `/bless `

[Cleric Class Only]<br/><br/>This allows a praying Cleric to add substantial bonuses for heroes fighting the battle.

# insight (Hybrid Command)
 - Usage: `[p]insight `
 - Slash Usage: `/insight `
 - Cooldown: `1 per 30.0 seconds`
 - Checks: `server_only`

[Psychic Class Only]<br/>This allows a Psychic to expose the current enemy's weakeness to the party.

# rage (Hybrid Command)
 - Usage: `[p]rage `
 - Slash Usage: `/rage `

[Berserker Class Only]<br/><br/>This allows a Berserker to add substantial attack bonuses for one battle.

# focus (Hybrid Command)
 - Usage: `[p]focus `
 - Slash Usage: `/focus `

[Wizard Class Only]<br/><br/>This allows a Wizard to add substantial magic bonuses for one battle.

# music (Hybrid Command)
 - Usage: `[p]music `
 - Slash Usage: `/music `

[Bard Class Only]<br/><br/>This allows a Bard to add substantial diplomacy bonuses for one battle.

# forge (Hybrid Command)
 - Usage: `[p]forge `
 - Slash Usage: `/forge `

[Tinkerer Class Only]<br/><br/>This allows a Tinkerer to forge two items into a device. (1h cooldown)

# skill (Hybrid Command)
 - Usage: `[p]skill [skill=None] [amount=1] `
 - Slash Usage: `/skill [skill=None] [amount=1] `
 - Cooldown: `1 per 2.0 seconds`

This allows you to spend skillpoints.<br/><br/>`[p]skill attack/charisma/intelligence`<br/>`[p]skill reset` Will allow you to reset your skill points for a cost.

# setinfo (Hybrid Command)
 - Usage: `[p]setinfo [set_name] `
 - Slash Usage: `/setinfo [set_name] `

Show set bonuses for the specified set.

# stats (Hybrid Command)
 - Usage: `[p]stats [user] `
 - Slash Usage: `/stats [user] `

This draws up a character sheet of you or an optionally specified member.

# unequip (Hybrid Command)
 - Usage: `[p]unequip <item> `
 - Slash Usage: `/unequip <item> `

This stashes a specified equipped item into your backpack.<br/><br/>Use `[p]unequip name of item` or `[p]unequip slot`

# equip (Hybrid Command)
 - Usage: `[p]equip <item> `
 - Slash Usage: `/equip <item> `

This equips an item from your backpack.

# backpack (Hybrid Command)
 - Usage: `[p]backpack [show_diff=False] [rarity=None] [slot] `
 - Slash Usage: `/backpack [show_diff=False] [rarity=None] [slot] `

This shows the contents of your backpack.<br/><br/>Give it a rarity and/or slot to filter what backpack items to show.<br/><br/>Selling:     `[p]backpack sell item_name`<br/>Trading:     `[p]backpack trade @user price item_name`<br/>Equip:       `[p]backpack equip item_name`<br/>Sell All:    `[p]backpack sellall rarity slot`<br/>Disassemble: `[p]backpack disassemble item_name`<br/><br/>Note: An item **degrade** level is how many rebirths it will last, before it is broken down.

## backpack trade (Hybrid Command)
 - Usage: `[p]backpack trade <buyer> [asking=1000] <item> `
 - Slash Usage: `/backpack trade <buyer> [asking=1000] <item> `

Trade an item from your backpack to another user.

## backpack eset (Hybrid Command)
 - Usage: `[p]backpack eset <set_name> `
 - Slash Usage: `/backpack eset <set_name> `
 - Cooldown: `1 per 600.0 seconds`

Equip all parts of a set that you own.

## backpack equip (Hybrid Command)
 - Usage: `[p]backpack equip <equip_item> `
 - Slash Usage: `/backpack equip <equip_item> `

Equip an item from your backpack.

## backpack sell (Hybrid Command)
 - Usage: `[p]backpack sell <item> `
 - Slash Usage: `/backpack sell <item> `
 - Cooldown: `3 per 60.0 seconds`

Sell an item from your backpack.

## backpack disassemble (Hybrid Command)
 - Usage: `[p]backpack disassemble <backpack_items> `
 - Slash Usage: `/backpack disassemble <backpack_items> `

Disassemble items from your backpack.<br/><br/>This will provide a chance for a chest,<br/>or the item might break while you are handling it...

## backpack sellall (Hybrid Command)
 - Usage: `[p]backpack sellall [rarity=None] [slot] `
 - Slash Usage: `/backpack sellall [rarity=None] [slot] `

Sell all items in your backpack. Optionally specify rarity or slot.

# ebackpack
 - Usage: `[p]ebackpack [show_diff=False] [rarity=None] [slot] `

This shows the contents of your backpack that can be equipped.<br/><br/>Give it a rarity and/or slot to filter what backpack items to show.<br/><br/>Note: An item **degrade** level is how many rebirths it will last, before it is broken down.

# cbackpack
 - Usage: `[p]cbackpack `

Complex backpack management tools.<br/><br/>Please read the usage instructions [here](https://github.com/aikaterna/gobcog/blob/master/docs/cbackpack.md)

## cbackpack sell
 - Usage: `[p]cbackpack sell <query> `
 - Cooldown: `3 per 60.0 seconds`

Sell items from your backpack.<br/><br/>Forged items cannot be sold using this command.<br/><br/>Please read the usage instructions [here](https://github.com/aikaterna/gobcog/blob/master/docs/cbackpack.md)

## cbackpack show
 - Usage: `[p]cbackpack show <query> `

This shows the contents of your backpack.<br/><br/>Please read the usage instructions [here](https://github.com/aikaterna/gobcog/blob/master/docs/cbackpack.md)

## cbackpack disassemble
 - Usage: `[p]cbackpack disassemble <query> `

Disassemble items from your backpack.<br/><br/>This will provide a chance for a chest,<br/>or the item might break while you are handling it...<br/><br/>Please read the usage instructions [here](https://github.com/aikaterna/gobcog/blob/master/docs/cbackpack.md)

# adventureset
 - Usage: `[p]adventureset `
 - Checks: `server_only`

Setup various adventure settings.

## adventureset easymode
 - Usage: `[p]adventureset easymode `
 - Restricted to: `BOT_OWNER`

[Owner] Set whether or not Adventure will be in easy mode.<br/><br/>Easy mode gives less rewards, but monster information is shown.

## adventureset cart
 - Usage: `[p]adventureset cart [channel] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

[Admin] Add or remove a text channel that the Trader cart can appear in.<br/><br/>If the channel is already in the list, it will be removed.<br/>Use `[p]adventureset cart` with no arguments to show the channel list.

## adventureset globalgod
 - Usage: `[p]adventureset globalgod <name> `
 - Restricted to: `BOT_OWNER`

[Owner] Set the default name of the god.

## adventureset clear
 - Usage: `[p]adventureset clear <users> `
 - Restricted to: `BOT_OWNER`

[Owner] Lets you clear multiple users character sheets.

## adventureset sepcurrency
 - Usage: `[p]adventureset sepcurrency `
 - Restricted to: `BOT_OWNER`

[Owner] Toggle whether the currency should be separated from main bot currency.

## adventureset cartroom
 - Usage: `[p]adventureset cartroom [room=None] `
 - Restricted to: `ADMIN`

[Admin] Lock carts to a specific text channel.

## adventureset showsettings
 - Usage: `[p]adventureset showsettings `
 - Cooldown: `1 per 4.0 seconds`
 - Checks: `server_only`

Display current settings.

## adventureset remove
 - Usage: `[p]adventureset remove <user> <full_item_name> `
 - Restricted to: `BOT_OWNER`

[Owner] Lets you remove an item from a user.<br/><br/>Use the full name of the item including the rarity characters like . or []  or {}.

## adventureset rebirthcost
 - Usage: `[p]adventureset rebirthcost <percentage> `
 - Checks: `check_global_setting_admin`

[Admin] Set what percentage of the user balance to charge for rebirths.<br/><br/>Unless the user's balance is under 1k, users that rebirth will be left with the base of 1k credits plus the remaining credit percentage after the rebirth charge.

## adventureset embeds
 - Usage: `[p]adventureset embeds `
 - Restricted to: `ADMIN`
 - Aliases: `embed`

[Admin] Set whether or not to use embeds for the adventure game.

## adventureset dailybonus
 - Usage: `[p]adventureset dailybonus <day> <percentage> `
 - Restricted to: `BOT_OWNER`

[Owner] Set the daily xp and currency bonus.<br/><br/>**percentage** must be between 0% and 100%.

## adventureset locks
 - Usage: `[p]adventureset locks `
 - Restricted to: `ADMIN`

[Admin] Reset Adventure locks.

### adventureset locks adventure
 - Usage: `[p]adventureset locks adventure `
 - Checks: `server_only`

[Admin] Reset the adventure game lock for the server.

### adventureset locks user
 - Usage: `[p]adventureset locks user <users> `
 - Restricted to: `BOT_OWNER`

[Owner] Reset a multiple adventurers lock.

## adventureset economy
 - Usage: `[p]adventureset economy `
 - Checks: `check_global_setting_admin, server_only and has_separated_economy`

[Admin] Manages the adventure economy.

### adventureset economy withdraw
 - Usage: `[p]adventureset economy withdraw `

[Admin] Toggle whether users are allowed to withdraw from adventure currency to main currency.

### adventureset economy rate
 - Usage: `[p]adventureset economy rate <rate_in> <rate_out> `
 - Restricted to: `BOT_OWNER`

[Owner] Set how much 1 bank credit is worth in adventure.<br/><br/>**rate_in**: Is how much gold you will get for 1 bank credit. Default is 10<br/>**rate_out**: Is how much gold is needed to convert to 1 bank credit. Default is 11

### adventureset economy tax
 - Usage: `[p]adventureset economy tax <taxes> `
 - Restricted to: `BOT_OWNER`

[Owner] Set the tax thresholds.<br/><br/>**gold** must be positive<br/>**tax** must be between 0 and 1.<br/><br/>Example: `[p]adventureset economy tax 10000,0.1 20000,0.2 ...`

### adventureset economy maxwithdraw
 - Usage: `[p]adventureset economy maxwithdraw <amount> `

[Admin] Set how much players are allowed to withdraw.

## adventureset globalcartname
 - Usage: `[p]adventureset globalcartname <name> `
 - Restricted to: `BOT_OWNER`

[Owner] Set the default name of the cart.

## adventureset carttime
 - Usage: `[p]adventureset carttime <time> `
 - Restricted to: `ADMIN`

[Admin] Set the cooldown of the cart.<br/>Time can be in seconds, minutes, hours, or days.<br/>Examples: `1h 30m`, `2 days`, `300 seconds`

## adventureset version
 - Usage: `[p]adventureset version `

Display the version of adventure being used.

## adventureset cartname
 - Usage: `[p]adventureset cartname <name> `
 - Restricted to: `ADMIN`

[Admin] Set the server's name of the cart.

## adventureset theme
 - Usage: `[p]adventureset theme <theme> `
 - Restricted to: `BOT_OWNER`

[Owner] Change the theme for adventure.<br/><br/>The default theme is `default`.<br/>More info can be found at: <https://github.com/aikaterna/gobcog#make-your-own-adventure-theme>

## adventureset restrict
 - Usage: `[p]adventureset restrict `
 - Restricted to: `BOT_OWNER`

[Owner] Set whether or not adventurers are restricted to one adventure at a time.

## adventureset god
 - Usage: `[p]adventureset god <name> `
 - Restricted to: `ADMIN`

[Admin] Set the server's name of the god.

# adventure (Hybrid Command)
 - Usage: `[p]adventure [challenge] `
 - Slash Usage: `/adventure [challenge] `
 - Aliases: `a`
 - Cooldown: `1 per 5.0 seconds`
 - Checks: `server_only`

This will send you on an adventure!<br/><br/>You play by reacting with the offered emojis.

