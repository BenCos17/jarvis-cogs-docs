# Chatchart Help

Show activity.

# chatchart
 - Usage: `[p]chatchart [channel=None] [messages=5000] `
 - Cooldown: `1 per 10.0 seconds`
 - Checks: `server_only`

Generates a pie chart, representing the last 5000 messages in the specified channel.

# serverchart
 - Usage: `[p]serverchart [messages=1000] `
 - Restricted to: `MOD`
 - Aliases: `serverchart`
 - Cooldown: `1 per 30.0 seconds`
 - Checks: `server_only`

Generates a pie chart, representing the last 1000 messages from every allowed channel in the server.<br/><br/>As example:<br/>For each channel that the bot is allowed to scan. It will take the last 1000 messages from each channel.<br/>And proceed to build a chart out of that.

# ccdeny
 - Usage: `[p]ccdeny <channel> `
 - Restricted to: `MOD`
 - Checks: `server_only`

Add a channel to deny chatchart use.

# ccdenylist
 - Usage: `[p]ccdenylist `
 - Restricted to: `MOD`
 - Checks: `server_only`

List the channels that are denied.

# ccallow
 - Usage: `[p]ccallow <channel> `
 - Restricted to: `MOD`
 - Checks: `server_only`

Remove a channel from the deny list to allow chatchart use.

# cclimit
 - Usage: `[p]cclimit [limit_amount=None] `
 - Restricted to: `BOT_OWNER`

Limit the amount of messages someone can request.<br/><br/>Use `0` for no limit.

