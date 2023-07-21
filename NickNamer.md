# NickNamer Help

NickNamer

# nick
 - Usage: `[p]nick <user> <reason> `
 - Restricted to: `MOD`

Forcibly change a user's nickname to a predefined string.

# cnick
 - Usage: `[p]cnick <user> <nickname> <reason> `
 - Restricted to: `MOD`

Forcibly change a user's nickname.

# freezenick
 - Usage: `[p]freezenick <user> <nickname> [reason] `
 - Restricted to: `MOD`

Freeze a users nickname.

# unfreezenick
 - Usage: `[p]unfreezenick <user> `
 - Restricted to: `MOD`

Unfreeze a user's nickname.

# tempnick
 - Usage: `[p]tempnick <user> <duration> <nickname> [reason] `
 - Restricted to: `MOD`

Temporarily rename a user.<br/>**IMPORTANT**: For better performance, temporary nicknames are checked in a 10 minute intervall.

# nickset
 - Usage: `[p]nickset `
 - Restricted to: `ADMIN`

Nicknamer settings

## nickset name
 - Usage: `[p]nickset name <name> `

Set the default name that will be applied when using ``[p]nick``

## nickset modlog
 - Usage: `[p]nickset modlog <true_or_false> `

Set if you would like to create a modlog entry everytime a nickname is being changed.

## nickset dm
 - Usage: `[p]nickset dm <true_or_false> `

Set if you would like the bot to DM the user who's nickname was changed.

# nickpurge
 - Usage: `[p]nickpurge <are_you_sure> `
 - Restricted to: `ADMIN`

Remove all nicknames in the server.

