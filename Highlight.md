# Highlight Help

Be notified when keywords are sent.

# highlight
 - Usage: `[p]highlight `
 - Checks: `server_only and restrictedhighlight_check`

Highlighting Commands.

## highlight server
 - Usage: `[p]highlight server `
 - Checks: `server_only`

Guild based highlighting commands.<br/><br/>Guild highlights take precedence over channel based.

### highlight server remove
 - Usage: `[p]highlight server remove <text> `

Remove highlighting for a server.<br/><br/>An optional channel can be provided to remove a highlight from that channel.

### highlight server boundary
 - Usage: `[p]highlight server boundary <state> [word] `

Use word boundaries for server highlighting.<br/><br/>Expects a valid bool. Not passing a word will enable/disable word boundaries for all<br/>highlights.

### highlight server add
 - Usage: `[p]highlight server add <text> `

Add a word to be highlighted on for the server.<br/><br/>        Text will be converted to lowercase.<br/>Can also provide an optional channel argument for<br/>        the highlight to be applied to that channel.<br/>        

### highlight server list
 - Usage: `[p]highlight server list `

Current highlight settings for a channel.<br/><br/>A channel argument can be supplied to view settings for said channel.

### highlight server bots
 - Usage: `[p]highlight server bots <state> [word] `

Enable highlighting of bot messages for server highlights.<br/><br/>Expects a valid bool. Not passing a word will enable/disable bot highlighting for all<br/>highlights.

### highlight server toggle
 - Usage: `[p]highlight server toggle <state> [word] `

Toggle highlighting for server highlights.<br/><br/>Must be a valid bool. Not passing a word will enable/disable highlighting for all<br/>highlights.

## highlight whitelist
 - Usage: `[p]highlight whitelist `

Manage highlight whitelist.<br/><br/>Whitelist takes priority over blacklist.

### highlight whitelist list
 - Usage: `[p]highlight whitelist list `

List those in your whitelist.

### highlight whitelist user
 - Usage: `[p]highlight whitelist user <user> `

Add or remove a member from highlight whitelist.<br/><br/>This is per server.

## highlight blacklist
 - Usage: `[p]highlight blacklist `

Manage highlight blacklist.<br/><br/>Whitelist takes priority over blacklist.

### highlight blacklist user
 - Usage: `[p]highlight blacklist user <user> `

Add or remove a member from highlight blacklist.<br/><br/>This is per server.

### highlight blacklist channel
 - Usage: `[p]highlight blacklist channel <channel> `

Add or remove a channel from highlight blacklist.<br/><br/>This is per server.

### highlight blacklist list
 - Usage: `[p]highlight blacklist list `

List your blacklist.

## highlight remove
 - Usage: `[p]highlight remove [channel=None] <text> `

Remove highlighting in a channel.<br/><br/>An optional channel can be provided to remove a highlight from that channel.

## highlight bots
 - Usage: `[p]highlight bots <state> [channel=None] [word] `

Enable highlighting of bot messages.<br/><br/>Expects a valid bool. Not passing a word will enable/disable bot highlighting for all<br/>highlights.

## highlight add
 - Usage: `[p]highlight add [channel=None] <text> `

Add a word to be highlighted on.<br/><br/>        Text will be converted to lowercase.<br/>Can also provide an optional channel argument for<br/>        the highlight to be applied to that channel.<br/>        

## highlight toggle
 - Usage: `[p]highlight toggle <state> [channel=None] [word] `

Toggle highlighting.<br/><br/>Must be a valid bool. Not passing a word will enable/disable highlighting for all<br/>highlights.

## highlight list
 - Usage: `[p]highlight list [channel=None] `

Current highlight settings for a channel.<br/><br/>A channel argument can be supplied to view settings for said channel.

## highlight cooldown
 - Usage: `[p]highlight cooldown [seconds=None] `

Set the cooldown for highlighted messages to be sent. Default is 60 seconds.<br/><br/>This is per server.<br/>Not providing a value will send the current set value.

## highlight boundary
 - Usage: `[p]highlight boundary <state> [channel=None] [word] `

Use word boundaries for highlighting.<br/><br/>Expects a valid bool. Not passing a word will enable/disable word boundaries for all<br/>highlights.

# highlightset
 - Usage: `[p]highlightset `
 - Restricted to: `BOT_OWNER`

Manage highlight settings.

## highlightset wipe
 - Usage: `[p]highlightset wipe <user> `

Wipe all highlights for a user.

## highlightset show
 - Usage: `[p]highlightset show `
 - Aliases: `settings and showsettings`

Show the current highlight settings.

## highlightset restrict
 - Usage: `[p]highlightset restrict <toggle> `

Restrict the use of highlights to users with mod/admin permissions.

## highlightset minlen
 - Usage: `[p]highlightset minlen <min_len> `

Set the minimum length of a highlight.

## highlightset colour
 - Usage: `[p]highlightset colour [colour] `
 - Aliases: `color`

Set the colour for the highlight embed.

## highlightset cooldown
 - Usage: `[p]highlightset cooldown <cooldown> `

Set the default cooldown of a highlight. (in seconds)<br/><br/>Users can override this by using the `highlight cooldown` command, but cannot go lower that what it defined.

## highlightset max
 - Usage: `[p]highlightset max <max_num> `

Set the max number of highlights a user can have.

