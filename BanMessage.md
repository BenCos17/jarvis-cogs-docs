# BanMessage Help

Send message on ban in a chosen channel. Supports images!

# banmessageset
 - Usage: `[p]banmessageset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

BanMessage settings.

## banmessageset unsetimage
 - Usage: `[p]banmessageset unsetimage `

Unset image for ban message.

## banmessageset removemessage
 - Usage: `[p]banmessageset removemessage `
 - Aliases: `deletemessage`

Remove ban message.

## banmessageset hackban
 - Usage: `[p]banmessageset hackban [enabled=None] `

Set if hackbans should trigger ban messages.<br/><br/>INFO: Hackbans are bans of users<br/>that weren't members of the server (also called preemptive bans).

## banmessageset addmessage
 - Usage: `[p]banmessageset addmessage <message> `

Add ban message.<br/><br/>Those fields will get replaced automatically:<br/>$username - The banned user's name<br/>$server - The name of the server<br/><br/>Note: Ban message can also have image.<br/>To set it, use `[p]banmessageset setimage`

## banmessageset setimage
 - Usage: `[p]banmessageset setimage `

Set image for ban message.

## banmessageset channel
 - Usage: `[p]banmessageset channel [channel=None] `

Set channel for ban messages. Leave empty to disable.

## banmessageset listmessages
 - Usage: `[p]banmessageset listmessages `

List ban message templates.

