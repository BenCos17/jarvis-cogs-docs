# AntiPhishing Help

Protects users against phishing attacks.

# checkphish
 - Usage: `[p]checkphish [url=None] `
 - Aliases: `checkforphish, checkscam, checkforscam and checkphishing`

Check if a url is a phishing scam.<br/><br/>You can either provide a url or reply to a message containing a url.

# antiphishing
 - Usage: `[p]antiphishing `
 - Restricted to: `ADMIN`
 - Aliases: `antiphish`
 - Checks: `server_only`

Settings to set up the anti-phishing integration.

## antiphishing action
 - Usage: `[p]antiphishing action <action> `

Choose the action that occurs when a user sends a phishing scam.<br/><br/>Options:<br/>`ignore` - Disables the anti-phishing integration (default)<br/>`notify` - Sends a message to the channel and says it's a phishing scam<br/>`delete` - Deletes the message<br/>`kick` - Kicks the author (also deletes the message)<br/>`ban` - Bans the author (also deletes the message)

## antiphishing stats
 - Usage: `[p]antiphishing stats `

Shows the current stats for the anti-phishing integration.

