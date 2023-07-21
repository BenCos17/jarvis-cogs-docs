# ReTrigger Help

Trigger bot events using regular expressions

## re-trigger modlog
 - Usage: `[p]re-trigger modlog `

Set which events to record in the modlog.

### re-trigger modlog settings (Slash Command)
 - Usage: `/re-trigger modlog settings `
 - Checks: `

Show retrigger's modlog settings for this server.

### re-trigger modlog bans (Slash Command)
 - Usage: `/re-trigger modlog bans `
 - Checks: `

Toggle custom ban messages in the modlog

### re-trigger modlog kicks (Slash Command)
 - Usage: `/re-trigger modlog kicks `
 - Checks: `

Toggle custom kick messages in the modlog

### re-trigger modlog filter (Slash Command)
 - Usage: `/re-trigger modlog filter `
 - Checks: `

Toggle custom filter messages in the modlog

### re-trigger modlog addroles (Slash Command)
 - Usage: `/re-trigger modlog addroles `
 - Checks: `

Toggle custom add role messages in the modlog

### re-trigger modlog removeroles (Slash Command)
 - Usage: `/re-trigger modlog removeroles `
 - Checks: `

Toggle custom remove role messages in the modlog

### re-trigger modlog channel (Slash Command)
 - Usage: `/re-trigger modlog channel [channel] `
 - `channel:` (Optional) …

 - Checks: `

Set the modlog channel for filtered words

## re-trigger allowlist
 - Usage: `[p]re-trigger allowlist `

Set allowlist options for ReTrigger.

### re-trigger allowlist add (Slash Command)
 - Usage: `/re-trigger allowlist add <trigger> [channel] [user] [role] `
 - `trigger:` (Required) …
 - `channel:` (Optional) …
 - `user:` (Optional) …
 - `role:` (Optional) …

 - Checks: `

Add a channel, user, or role to a triggers allowlist

### re-trigger allowlist remove (Slash Command)
 - Usage: `/re-trigger allowlist remove <trigger> [channel] [user] [role] `
 - `trigger:` (Required) …
 - `channel:` (Optional) …
 - `user:` (Optional) …
 - `role:` (Optional) …

 - Checks: `

Remove a channel, user, or role from a triggers allowlist

## re-trigger blocklist
 - Usage: `[p]re-trigger blocklist `

Set blocklist options for ReTrigger.

### re-trigger blocklist add (Slash Command)
 - Usage: `/re-trigger blocklist add <trigger> [channel] [user] [role] `
 - `trigger:` (Required) …
 - `channel:` (Optional) …
 - `user:` (Optional) …
 - `role:` (Optional) …

 - Checks: `

Add a channel, user, or role to a triggers blocklist

### re-trigger blocklist remove (Slash Command)
 - Usage: `/re-trigger blocklist remove <trigger> [channel] [user] [role] `
 - `trigger:` (Required) …
 - `channel:` (Optional) …
 - `user:` (Optional) …
 - `role:` (Optional) …

 - Checks: `

Remove a channel, user, or role from a triggers blocklist

## re-trigger edit
 - Usage: `[p]re-trigger edit `

Edit various settings in a set trigger.

### re-trigger edit cooldown (Slash Command)
 - Usage: `/re-trigger edit cooldown <trigger> <time> [style] `
 - `trigger:` (Required) …
 - `time:` (Required) …
 - `style:` (Optional) …

Set cooldown options for ReTrigger

### re-trigger edit regex (Slash Command)
 - Usage: `/re-trigger edit regex <trigger> <regex> `
 - `trigger:` (Required) …
 - `regex:` (Required) …

 - Checks: `

Edit the regex of a saved trigger.

### re-trigger edit nsfw (Slash Command)
 - Usage: `/re-trigger edit nsfw <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Toggle whether a trigger is considered age-restricted.

### re-trigger edit readembeds (Slash Command)
 - Usage: `/re-trigger edit readembeds <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Toggle whether to include embed contents in searched text.

### re-trigger edit readfilenames (Slash Command)
 - Usage: `/re-trigger edit readfilenames <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Toggle whether to search message attachment filenames.

### re-trigger edit reply (Slash Command)
 - Usage: `/re-trigger edit reply <trigger> [set_to] `
 - `trigger:` (Required) …
 - `set_to:` (Optional) True will reply with mention, False will reply without mention, blank will not use a reply.

 - Checks: `

Set whether or not to reply to the triggered message.

### re-trigger edit thread (Slash Command)
 - Usage: `/re-trigger edit thread <trigger> [set_to] [thread_name] `
 - `trigger:` (Required) …
 - `set_to:` (Optional) True will create a Public Thread, False will create a Private Thread, blank will not create a…
 - `thread_name:` (Optional) The name of the thread created. You can use replacements like in text responses.

 - Checks: `

Set whether or not to create a thread from the trigger.

### re-trigger edit tts (Slash Command)
 - Usage: `/re-trigger edit tts <trigger> <set_to> `
 - `trigger:` (Required) …
 - `set_to:` (Required) …

Set whether or not to send the message with text-to-speech.

### re-trigger edit usermention (Slash Command)
 - Usage: `/re-trigger edit usermention <trigger> <set_to> `
 - `trigger:` (Required) …
 - `set_to:` (Required) …

 - Checks: `

Set whether or not this trigger can mention users

### re-trigger edit everyonemention (Slash Command)
 - Usage: `/re-trigger edit everyonemention <trigger> <set_to> `
 - `trigger:` (Required) …
 - `set_to:` (Required) …

 - Checks: `

Set whether or not this trigger can mention everyone

### re-trigger edit rolemention (Slash Command)
 - Usage: `/re-trigger edit rolemention <trigger> <set_to> `
 - `trigger:` (Required) …
 - `set_to:` (Required) …

 - Checks: `

Set whether or not this trigger can mention roles

### re-trigger edit edited (Slash Command)
 - Usage: `/re-trigger edit edited <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Toggle whether to search message edits.

### re-trigger edit ignorecommands (Slash Command)
 - Usage: `/re-trigger edit ignorecommands <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Toggle whether a trigger will ignore commands.

### re-trigger edit text (Slash Command)
 - Usage: `/re-trigger edit text <trigger> <text> `
 - `trigger:` (Required) …
 - `text:` (Required) …

 - Checks: `

Edit the text of a saved trigger.

### re-trigger edit chance (Slash Command)
 - Usage: `/re-trigger edit chance <trigger> <chance> `
 - `trigger:` (Required) …
 - `chance:` (Required) …

 - Checks: `

Edit the chance a trigger will execute.

### re-trigger edit command (Slash Command)
 - Usage: `/re-trigger edit command <trigger> <command> `
 - `trigger:` (Required) …
 - `command:` (Required) …

 - Checks: `

Edit the command a trigger runs.

### re-trigger edit role (Slash Command)
 - Usage: `/re-trigger edit role <trigger> <role> `
 - `trigger:` (Required) …
 - `role:` (Required) …

 - Checks: `

Edit the added or removed role of a saved trigger.

### re-trigger edit reaction (Slash Command)
 - Usage: `/re-trigger edit reaction <trigger> <emoji> `
 - `trigger:` (Required) …
 - `emoji:` (Required) …

Edit the emoji reaction of a saved trigger.

### re-trigger edit enable (Slash Command)
 - Usage: `/re-trigger edit enable <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Enable a trigger

### re-trigger edit disable (Slash Command)
 - Usage: `/re-trigger edit disable <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Disable a trigger

## re-trigger list (Slash Command)
 - Usage: `/re-trigger list [trigger] [server_id] `
 - `trigger:` (Optional) …
 - `server_id:` (Optional) Only available to bot owner

List information about a trigger

## re-trigger remove (Slash Command)
 - Usage: `/re-trigger remove <trigger> `
 - `trigger:` (Required) …

 - Checks: `

Remove a specified trigger

## re-trigger explain (Slash Command)
 - Usage: `/re-trigger explain [page_num] `
 - `page_num:` (Optional) …

Explain how to use retrigger

## re-trigger text (Slash Command)
 - Usage: `/re-trigger text <name> <regex> <text> [delete_after] `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `text:` (Required) …
 - `delete_after:` (Optional) …

 - Checks: `

Add a text response trigger

## re-trigger dm (Slash Command)
 - Usage: `/re-trigger dm <name> <regex> <text> `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `text:` (Required) …

 - Checks: `

Add a dm response trigger

## re-trigger dmme (Slash Command)
 - Usage: `/re-trigger dmme <name> <regex> <text> `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `text:` (Required) …

 - Checks: `

Add a trigger to dm yourself

## re-trigger rename (Slash Command)
 - Usage: `/re-trigger rename <name> <regex> <text> `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `text:` (Required) …

 - Checks: `

Add a trigger to rename users

## re-trigger ban (Slash Command)
 - Usage: `/re-trigger ban <name> <regex> `
 - `name:` (Required) …
 - `regex:` (Required) …

 - Checks: `

Add a trigger to ban users

## re-trigger kick (Slash Command)
 - Usage: `/re-trigger kick <name> <regex> `
 - `name:` (Required) …
 - `regex:` (Required) …

 - Checks: `

Add a trigger to kick users

## re-trigger command (Slash Command)
 - Usage: `/re-trigger command <name> <regex> <command> `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `command:` (Required) …

 - Checks: `

Add a command trigger

## re-trigger filter (Slash Command)
 - Usage: `/re-trigger filter <name> <regex> [check_filenames] `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `check_filenames:` (Optional) …

 - Checks: `

Add a trigger to filter messages

## re-trigger addrole (Slash Command)
 - Usage: `/re-trigger addrole <name> <regex> <role> `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `role:` (Required) …

 - Checks: `

Add a trigger to add a role

## re-trigger removerole (Slash Command)
 - Usage: `/re-trigger removerole <name> <regex> <role> `
 - `name:` (Required) …
 - `regex:` (Required) …
 - `role:` (Required) …

 - Checks: `

Add a trigger to remove a role

# retrigger
 - Usage: `[p]retrigger `
 - Checks: `server_only`

Setup automatic triggers based on regular expressions<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger random
 - Usage: `[p]retrigger random <name> <regex> `
 - Restricted to: `MOD`
 - Aliases: `randomtext and rtext`

Add a random text response trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger react
 - Usage: `[p]retrigger react <name> <regex> <emojis> `
 - Restricted to: `MOD`

Add a reaction trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`emojis` the emojis to react with when triggered separated by spaces<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger addrole
 - Usage: `[p]retrigger addrole <name> <regex> <roles> `
 - Restricted to: `MOD`

Add a trigger to add a role<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`[role...]` the roles applied when the regex pattern matches space separated<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger allowlist
 - Usage: `[p]retrigger allowlist `
 - Restricted to: `MOD`
 - Aliases: `whitelist`

Set allowlist options for retrigger<br/><br/>allowlisting supports channels, users, or roles<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger allowlist remove
 - Usage: `[p]retrigger allowlist remove <triggers> <channel_user_role> `
 - Restricted to: `MOD`
 - Aliases: `rem and del`

Remove a channel, user, or role from triggers allowlist<br/><br/>`<trigger>` is the name of the trigger.<br/>`[channel_user_role...]` is the channel, user or role to remove from the allowlist<br/>(You can supply more than one of any at a time)<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger allowlist add
 - Usage: `[p]retrigger allowlist add <triggers> <channel_user_role> `
 - Restricted to: `MOD`

Add a channel, user, or role to triggers allowlist<br/><br/>`<trigger>` is the name of the trigger.<br/>`[channel_user_role...]` is the channel, user or role to allowlist<br/>(You can supply more than one of any at a time)<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger filter
 - Usage: `[p]retrigger filter <name> [check_filenames=False] <regex> `
 - Restricted to: `MOD`
 - Aliases: `deletemsg`

Add a trigger to delete a message<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger list
 - Usage: `[p]retrigger list [server_id=None] [trigger=None] `

List information about triggers.<br/><br/>`[trigger]` if supplied provides information about named trigger.<br/>⏯️ will toggle the displayed triggers active setting<br/>❎ will toggle the displayed trigger to be not active<br/>✅ will toggle the displayed trigger to be active<br/>🚮 will delete the displayed trigger<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger randomimage
 - Usage: `[p]retrigger randomimage <name> <regex> `
 - Restricted to: `MOD`
 - Aliases: `randimage, randimg, rimage and rimg`

Add a random image/file response trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger dm
 - Usage: `[p]retrigger dm <name> <regex> <text> `
 - Restricted to: `MOD`

Add a dm response trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`<text>` response of the trigger<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger text
 - Usage: `[p]retrigger text <name> <regex> [delete_after=None] <text> `
 - Restricted to: `MOD`

Add a text response trigger<br/><br/>`<name>` name of the trigger.<br/>`<regex>` the regex that will determine when to respond.<br/>`[delete_after]` Optionally have the text autodelete must include units e.g. 2m.<br/>`<text>` response of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger publish
 - Usage: `[p]retrigger publish <name> <regex> `
 - Restricted to: `MOD`

Add a trigger to automatically publish content in news channels.<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger remove
 - Usage: `[p]retrigger remove <trigger> `
 - Restricted to: `MOD`
 - Aliases: `del, rem and delete`

Remove a specified trigger<br/><br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger resize
 - Usage: `[p]retrigger resize <name> <regex> [image_url=None] `
 - Restricted to: `MOD`
 - Checks: `ReTrigger`

Add an image to resize in response to a trigger<br/>this will attempt to resize the image based on length of matching regex<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`[image_url]` optional image_url if none is provided the bot will ask to upload an image<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger multi
 - Usage: `[p]retrigger multi <name> <regex> <multi> `
 - Restricted to: `ADMIN`

Add a multiple response trigger<br/><br/>- `<name>` name of the trigger.<br/>- `<regex>` the regex that will determine when to respond.<br/>- `<multi>` The actions you want the trigger to perform.<br/> - `dm:` DM the message author something.<br/> - `dmme:` DM the trigger author something.<br/> - `add:` or `remove:` Roles which can be added/removed.<br/> - `ban:` True to ban the user who sent the message.<br/> - `kick:` True to kick the user who sent the message.<br/> - `text:` The text to send in the channel when triggers.<br/> - `react:` The emojis to react to the triggered messages with.<br/> - `rename:` What to change the message authors nickname to.<br/> - `command:` The bot command to run when triggered. Don't include a prefix.<br/> - `filter:` True to delete the triggered message.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger deleteallbyuser
 - Usage: `[p]retrigger deleteallbyuser <user_id> `
 - Restricted to: `BOT_OWNER`

Delete all triggers created by a specified user ID.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger edit
 - Usage: `[p]retrigger edit `
 - Restricted to: `MOD`

Edit various settings in a set trigger.<br/><br/>Note: Only the server owner, Bot owner, or original<br/>author can edit a saved trigger. Multi triggers<br/>cannot be edited.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit readthreads
 - Usage: `[p]retrigger edit readthreads <trigger> `
 - Restricted to: `MOD`
 - Aliases: `readthread`

Toggle whether a filter trigger will check thread titles.<br/>`<trigger>` is the name of the trigger.<br/><br/>This will toggle whether filter triggers are allowed to delete<br/>threads that are matched based on the thread title. This is enabled by default<br/>so if you only want filter triggers to work on messages disable this.<br/><br/># Note: This also requires the bot to have `manage_threads` permission<br/>in the channel that the threads are created to work.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit disable
 - Usage: `[p]retrigger edit disable <trigger> `
 - Restricted to: `MOD`

Disable a trigger<br/><br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit cooldown
 - Usage: `[p]retrigger edit cooldown <trigger> [time=0] [style=server] `
 - Restricted to: `MOD`

Set cooldown options for retrigger<br/><br/>`<trigger>` is the name of the trigger.<br/>`<time>` is a time in seconds until the trigger will run again<br/>set a time of 0 or less to remove the cooldown<br/>`[style=server]` must be either `server`, `server`, `channel`, `user`, or `member`<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit react
 - Usage: `[p]retrigger edit react <trigger> <emojis> `
 - Restricted to: `MOD`
 - Aliases: `emojis`

Edit the emoji reactions of a saved trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<emojis>` The new emojis to be used in the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit chance
 - Usage: `[p]retrigger edit chance <trigger> [chance=0] `
 - Restricted to: `MOD`
 - Aliases: `chances`

Edit the chance a trigger will execute.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<chance>` The chance the trigger will execute in form of 1 in chance.<br/><br/>Set the `chance` to 0 to remove the chance and always perform the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit usermention
 - Usage: `[p]retrigger edit usermention <trigger> [set_to=False] `
 - Restricted to: `MOD`
 - Aliases: `userping`

Set whether or not this trigger can mention users<br/><br/>`<trigger>` is the name of the trigger.<br/>`[set_to]` either `true` or `false` on whether to allow this trigger<br/>to actually ping the users in the message.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit regex
 - Usage: `[p]retrigger edit regex <trigger> <regex> `
 - Restricted to: `MOD`

Edit the regex of a saved trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<regex>` The new regex pattern to use.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit enable
 - Usage: `[p]retrigger edit enable <trigger> `
 - Restricted to: `MOD`

Enable a trigger<br/><br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit readfilenames
 - Usage: `[p]retrigger edit readfilenames <trigger> `
 - Restricted to: `MOD`
 - Aliases: `filenames`

Toggle whether to search message attachment filenames.<br/><br/>Note: This will append all attachments in a message to the message content. This **will not**<br/>download and read file content using regex.<br/><br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit everyonemention
 - Usage: `[p]retrigger edit everyonemention <trigger> [set_to=False] `
 - Restricted to: `MOD`
 - Aliases: `everyoneping`

Set whether or not to send this trigger can mention everyone<br/><br/>`<trigger>` is the name of the trigger.<br/>`[set_to]` either `true` or `false` on whether to allow this trigger<br/>to actually ping everyone if the bot has correct permissions.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit deleteafter
 - Usage: `[p]retrigger edit deleteafter <trigger> [delete_after] `
 - Restricted to: `MOD`
 - Aliases: `autodelete and delete`

Edit the delete_after parameter of a saved text trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<delete_after>` The time until the message is deleted must include units.<br/>Example: `[p]retrigger edit deleteafter trigger 2 minutes`<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit ignorecommands
 - Usage: `[p]retrigger edit ignorecommands <trigger> `
 - Restricted to: `MOD`

Toggle the trigger ignoring command messages entirely.<br/><br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit reply
 - Usage: `[p]retrigger edit reply <trigger> [set_to=None] `
 - Restricted to: `MOD`
 - Aliases: `replies`

Set whether or not to reply to the triggered message<br/><br/>`<trigger>` is the name of the trigger.<br/>`[set_to]` `True` will reply with a notificaiton, `False` will reply without a notification,<br/>leaving this blank will clear replies entirely.<br/><br/>Note: This is only availabe for Red 3.4.6/discord.py 1.6.0 or greater.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit ocr
 - Usage: `[p]retrigger edit ocr <trigger> `
 - Restricted to: `MOD`
 - Checks: `ReTrigger`

Toggle whether to use Optical Character Recognition to search for text within images.<br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit rolemention
 - Usage: `[p]retrigger edit rolemention <trigger> [set_to=False] `
 - Restricted to: `MOD`
 - Aliases: `roleping`

Set whether or not to send this trigger will allow role mentions<br/><br/>`<trigger>` is the name of the trigger.<br/>`[set_to]` either `true` or `false` on whether to allow this trigger<br/>to actually ping roles if the bot has correct permissions.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit nsfw
 - Usage: `[p]retrigger edit nsfw <trigger> `
 - Restricted to: `MOD`

Toggle whether a trigger is considered NSFW.<br/>This will prevent the trigger from activating in non-NSFW channels.<br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit command
 - Usage: `[p]retrigger edit command <trigger> <command> `
 - Restricted to: `MOD`
 - Aliases: `cmd`

Edit the text of a saved trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<command>` The new command for the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit edited
 - Usage: `[p]retrigger edit edited <trigger> `
 - Restricted to: `MOD`

Toggle whether the bot will listen to edited messages as well as on_message for<br/>the specified trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit readembeds
 - Usage: `[p]retrigger edit readembeds <trigger> `
 - Restricted to: `MOD`

Toggle whether a trigger will check embeds.<br/>This will allow the additional searching of Embed content.<br/>`<trigger>` is the name of the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit thread
 - Usage: `[p]retrigger edit thread <trigger> [public_or_private=None] [thread_name] `
 - Restricted to: `MOD`
 - Aliases: `makethread and createthread`

Set whether or not this trigger will attempt to create a private thread on the triggered<br/>message. This will automatically add the user who triggered this to the thread.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<public_or_private>` `True` will create a public thread, `False` will create a private thread. `None`<br/>or leaving this option blank will tell the trigger not to create a thread.<br/>`<thread_name>` The name of the thread created. This uses replacements if you want dynamic<br/>information such as the users name, etc.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit text
 - Usage: `[p]retrigger edit text <trigger> <text> `
 - Restricted to: `MOD`
 - Aliases: `msg`

Edit the text of a saved trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<text>` The new text to respond with.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit tts
 - Usage: `[p]retrigger edit tts <trigger> [set_to=False] `
 - Restricted to: `MOD`
 - Aliases: `texttospeech and text-to-speech`

Set whether or not to send the message with text-to-speech<br/><br/>`<trigger>` is the name of the trigger.<br/>`[set_to]` either `true` or `false` on whether to send the text<br/>reply with text-to-speech enabled.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger edit role
 - Usage: `[p]retrigger edit role <trigger> <roles> `
 - Restricted to: `MOD`
 - Aliases: `roles`

Edit the added or removed roles of a saved trigger.<br/><br/>`<trigger>` is the name of the trigger.<br/>`<roles>` space separated list of roles or ID's to edit on the trigger.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger explain
 - Usage: `[p]retrigger explain [page_num=1] `

Explain how to use retrigger<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger rename
 - Usage: `[p]retrigger rename <name> <regex> <text> `
 - Restricted to: `MOD`

Add trigger to rename users<br/><br/>`<name>` name of the trigger.<br/>`<regex>` the regex that will determine when to respond.<br/>`<text>` new users nickanme.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger ban
 - Usage: `[p]retrigger ban <name> <regex> `
 - Restricted to: `MOD`

Add a trigger to ban users for saying specific things found with regex<br/>This respects hierarchy so ensure the bot role is lower in the list<br/>than mods and admin so they don't get banned by accident<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger modlog
 - Usage: `[p]retrigger modlog `
 - Restricted to: `MOD`

Set which events to record in the modlog.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog bans
 - Usage: `[p]retrigger modlog bans `
 - Restricted to: `MOD`
 - Aliases: `ban`

Toggle custom ban messages in the modlog<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog kicks
 - Usage: `[p]retrigger modlog kicks `
 - Restricted to: `MOD`
 - Aliases: `kick`

Toggle custom kick messages in the modlog<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog settings
 - Usage: `[p]retrigger modlog settings `
 - Aliases: `list`

Show the current modlog settings for this server.<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog removeroles
 - Usage: `[p]retrigger modlog removeroles `
 - Restricted to: `MOD`
 - Aliases: `removerole, remrole and rolerem`

Toggle custom add role messages in the modlog<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog addroles
 - Usage: `[p]retrigger modlog addroles `
 - Restricted to: `MOD`
 - Aliases: `addrole`

Toggle custom add role messages in the modlog<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog channel
 - Usage: `[p]retrigger modlog channel <channel> `
 - Restricted to: `MOD`

Set the modlog channel for filtered words<br/><br/>`<channel>` The channel you would like filtered word notifications to go<br/>Use `none` or `clear` to not show any modlogs<br/>User `default` to use the built in modlog channel<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger modlog filter
 - Usage: `[p]retrigger modlog filter `
 - Restricted to: `MOD`
 - Aliases: `delete, filters and deletes`

Toggle custom filter messages in the modlog<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger command
 - Usage: `[p]retrigger command <name> <regex> <command> `
 - Restricted to: `MOD`
 - Aliases: `cmd`

Add a command trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`<command>` the command that will be triggered, do not add [p] prefix<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger image
 - Usage: `[p]retrigger image <name> <regex> [image_url=None] `
 - Restricted to: `MOD`

Add an image/file response trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`image_url` optional image_url if none is provided the bot will ask to upload an image<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger kick
 - Usage: `[p]retrigger kick <name> <regex> `
 - Restricted to: `MOD`

Add a trigger to kick users for saying specific things found with regex<br/>This respects hierarchy so ensure the bot role is lower in the list<br/>than mods and admin so they don't get kicked by accident<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger blocklist
 - Usage: `[p]retrigger blocklist `
 - Restricted to: `MOD`
 - Aliases: `blacklist`

Set blocklist options for retrigger<br/><br/>blocklisting supports channels, users, or roles<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger blocklist add
 - Usage: `[p]retrigger blocklist add <triggers> <channel_user_role> `
 - Restricted to: `MOD`

Add a channel, user, or role to triggers blocklist<br/><br/>`<trigger>` is the name of the trigger.<br/>`[channel_user_role...]` is the channel, user or role to blocklist<br/>(You can supply more than one of any at a time)<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

### retrigger blocklist remove
 - Usage: `[p]retrigger blocklist remove <triggers> <channel_user_role> `
 - Restricted to: `MOD`
 - Aliases: `rem and del`

Remove a channel, user, or role from triggers blocklist<br/><br/>`<trigger>` is the name of the trigger.<br/>`[channel_user_role...]` is the channel, user or role to remove from the blocklist<br/>(You can supply more than one of any at a time)<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger imagetext
 - Usage: `[p]retrigger imagetext <name> <regex> <text> [image_url=None] `
 - Restricted to: `MOD`

Add an image/file response with text trigger<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`<text>` the triggered text response<br/>`[image_url]` optional image_url if none is provided the bot will ask to upload an image<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger dmme
 - Usage: `[p]retrigger dmme <name> <regex> <text> `
 - Restricted to: `MOD`

Add trigger to DM yourself<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`<text>` response of the trigger<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

## retrigger removerole
 - Usage: `[p]retrigger removerole <name> <regex> <roles> `
 - Restricted to: `MOD`

Add a trigger to remove a role<br/><br/>`<name>` name of the trigger<br/>`<regex>` the regex that will determine when to respond<br/>`[role...]` the roles applied when the regex pattern matches space separated<br/><br/>See https://regex101.com/ for help building a regex pattern.<br/>See `[p]retrigger explain` or click the link below for more details.<br/>[For more details click here.](https://github.com/TrustyJAID/Trusty-cogs/blob/master/retrigger/README.md)

