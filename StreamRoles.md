# StreamRoles Help

Give current twitch streamers in your server a role.

# streamrole
 - Usage: `[p]streamrole `
 - Restricted to: `ADMIN`
 - Aliases: `streamroles`
 - Checks: `server_only`

Manage settings for StreamRoles.

## streamrole whitelist
 - Usage: `[p]streamrole whitelist `

Manage the whitelist.

### streamrole whitelist remove
 - Usage: `[p]streamrole whitelist remove <user_or_role> `

Remove a member or role from the whitelist.

### streamrole whitelist show
 - Usage: `[p]streamrole whitelist show `

Show the whitelisted members and roles in this server.

### streamrole whitelist add
 - Usage: `[p]streamrole whitelist add <user_or_role> `

Add a member or role to the whitelist.

## streamrole setmode
 - Usage: `[p]streamrole setmode <mode> `

Set the user filter mode to blacklist or whitelist.

## streamrole games
 - Usage: `[p]streamrole games `

Manage the game whitelist.<br/><br/>Adding games to the whitelist will make the bot only add the streamrole<br/>to members streaming those games. If the game whitelist is empty, the<br/>game being streamed won't be checked before adding the streamrole.

### streamrole games remove
 - Usage: `[p]streamrole games remove <game> `

Remove a game from the game whitelist.

### streamrole games clear
 - Usage: `[p]streamrole games clear `

Clear the game whitelist for this server.

### streamrole games add
 - Usage: `[p]streamrole games add <game> `

Add a game to the game whitelist.<br/><br/>This should *exactly* match the name of the game being played<br/>by the streamer as shown in Discord or on Twitch.

### streamrole games show
 - Usage: `[p]streamrole games show `

Show the game whitelist for this server.

## streamrole forceupdate
 - Usage: `[p]streamrole forceupdate `

Force the bot to reassign streamroles to members in this server.<br/><br/>This command forces the bot to inspect the streaming status of<br/>all current members of the server, and assign (or remove) the<br/>streamrole.

## streamrole blacklist
 - Usage: `[p]streamrole blacklist `

Manage the blacklist.

### streamrole blacklist show
 - Usage: `[p]streamrole blacklist show `

Show the blacklisted members and roles in this server.

### streamrole blacklist add
 - Usage: `[p]streamrole blacklist add <user_or_role> `

Add a member or role to the blacklist.

### streamrole blacklist remove
 - Usage: `[p]streamrole blacklist remove <user_or_role> `

Remove a member or role from the blacklist.

## streamrole alerts
 - Usage: `[p]streamrole alerts `

Manage streamalerts for those who receive the streamrole.

### streamrole alerts autodelete
 - Usage: `[p]streamrole alerts autodelete <true_or_false> `

Enable or disable alert autodeletion.<br/><br/>This is enabled by default. When enabled, alerts will be deleted<br/>once the streamer's role is removed.

### streamrole alerts setchannel
 - Usage: `[p]streamrole alerts setchannel <channel> `

Set the channel for streamrole alerts.

### streamrole alerts setenabled
 - Usage: `[p]streamrole alerts setenabled <true_or_false> `

Enable or disable streamrole alerts.

## streamrole setrole
 - Usage: `[p]streamrole setrole <role> `

Set the role which is given to streamers.

