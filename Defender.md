# Defender Help

Security tools to protect communities

# dset
 - Usage: `[p]dset `
 - Restricted to: `ADMIN`
 - Aliases: `defset`
 - Checks: `server_only`

Defender system settings

## dset commentanalysis
 - Usage: `[p]dset commentanalysis `
 - Restricted to: `ADMIN`
 - Aliases: `ca`

Comment analysis configuration<br/><br/>See [p]defender status for more information about this module

### dset commentanalysis deletemessage
 - Usage: `[p]dset commentanalysis deletemessage <on_or_off> `

Toggles whether to delete the offending message

### dset commentanalysis wdchecks
 - Usage: `[p]dset commentanalysis wdchecks [conditions] `

Implement advanced Warden based checks<br/><br/>Issuing this command with no arguments will show the current checks<br/>Passing 'remove' will remove existing checks

### dset commentanalysis reason
 - Usage: `[p]dset commentanalysis reason <reason> `

Sets a reason for the action (modlog use)

### dset commentanalysis wipe
 - Usage: `[p]dset commentanalysis wipe <days> `

Sets how many days worth of messages to delete if the action is ban<br/><br/>Setting 0 will not delete any message

### dset commentanalysis rank
 - Usage: `[p]dset commentanalysis rank <rank> `

Sets target rank

### dset commentanalysis attributes
 - Usage: `[p]dset commentanalysis attributes `

Setup the attributes that CA will check

### dset commentanalysis threshold
 - Usage: `[p]dset commentanalysis threshold <threshold> `

Sets the threshold that will trigger CA's action (20-100)

### dset commentanalysis action
 - Usage: `[p]dset commentanalysis action <action> `

Sets action (ban, kick, softban, punish or none (notification only))

### dset commentanalysis enable
 - Usage: `[p]dset commentanalysis enable <on_or_off> `

Toggles comment analysis

### dset commentanalysis token
 - Usage: `[p]dset commentanalysis token <token> `

Sets Perspective API token<br/><br/>https://developers.perspectiveapi.com/s/docs

## dset joinmonitor
 - Usage: `[p]dset joinmonitor `
 - Restricted to: `ADMIN`
 - Aliases: `jm`

Join monitor auto module configuration<br/><br/>See [p]defender status for more information about this module

### dset joinmonitor notifynew
 - Usage: `[p]dset joinmonitor notifynew <hours> `

Enables notifications for users younger than X hours<br/><br/>Use 0 hours to disable notifications

### dset joinmonitor wdchecks
 - Usage: `[p]dset joinmonitor wdchecks [conditions] `

Implement advanced Warden based checks<br/><br/>Issuing this command with no arguments will show the current checks<br/>Passing 'remove' will remove existing checks

### dset joinmonitor minutes
 - Usage: `[p]dset joinmonitor minutes <minutes> `

Sets minutes (X users joined in Y minutes)

### dset joinmonitor users
 - Usage: `[p]dset joinmonitor users <users> `

Sets users (X users joined in Y minutes)

### dset joinmonitor enable
 - Usage: `[p]dset joinmonitor enable <on_or_off> `

Toggles join monitor

### dset joinmonitor verificationlevel
 - Usage: `[p]dset joinmonitor verificationlevel `

Raises the server's verification level on raids<br/><br/>You can find a full description of Discord's verification levels in<br/>the server's settings "Moderation" tab.<br/><br/>Verification levels:<br/>0 - No action<br/>1 - Low: verified email<br/>2 - Medium: must be registered for longer than 5 minutes<br/>3 - High: must be a member of this server for longer than 10 minutes<br/>4 - Highest: must have a verified phone on their Discord account

## dset alert
 - Usage: `[p]dset alert `
 - Restricted to: `ADMIN`

Alert manual module configuration<br/><br/>See [p]defender status for more information about this module

### dset alert enable
 - Usage: `[p]dset alert enable <on_or_off> `

Toggle alert manual module

## dset emergency
 - Usage: `[p]dset emergency `
 - Restricted to: `ADMIN`

Emergency mode configuration<br/><br/>See [p]defender status for more information about emergency mode

### dset emergency modules
 - Usage: `[p]dset emergency modules `

Sets emergency modules<br/><br/>Emergency modules will be rendered available to helper roles<br/>during emergency mode. Selecting no modules to this command will<br/>disable emergency mode.<br/>Available emergency modules: voteout, vaporize, silence

### dset emergency minutes
 - Usage: `[p]dset emergency minutes <minutes> `

Sets max inactivity minutes for staff<br/><br/>After X minutes of inactivity following an alert emergency<br/>mode will be engaged and helper roles will be able to use<br/>the emergency modules.

## dset voteout
 - Usage: `[p]dset voteout `
 - Restricted to: `ADMIN`

Voteout manual module configuration<br/><br/>See [p]defender status for more information about this module

### dset voteout votes
 - Usage: `[p]dset voteout votes <votes> `

Sets required votes number for it to pass

### dset voteout wipe
 - Usage: `[p]dset voteout wipe <days> `

Sets how many days worth of messages to delete if the action is ban<br/><br/>Setting 0 will not delete any message

### dset voteout action
 - Usage: `[p]dset voteout action <action> `

Sets action (ban, kick, softban, punish)

### dset voteout rank
 - Usage: `[p]dset voteout rank <rank> `

Sets target rank

### dset voteout enable
 - Usage: `[p]dset voteout enable <on_or_off> `

Toggles voteout

## dset silence
 - Usage: `[p]dset silence `
 - Restricted to: `ADMIN`

Silence manual module configuration<br/><br/>See [p]defender status for more information about this module

### dset silence enable
 - Usage: `[p]dset silence enable <on_or_off> `

Toggle silence manual module

## dset warden
 - Usage: `[p]dset warden `
 - Restricted to: `ADMIN`
 - Aliases: `wd`

Warden auto module configuration<br/><br/>See [p]defender status for more information about this module

### dset warden regexsafetychecks
 - Usage: `[p]dset warden regexsafetychecks <on_or_off> `
 - Restricted to: `BOT_OWNER`

Globally toggles the safety checks for user defined regex<br/><br/>These checks disable Warden rules with regex that takes too long to be evaluated. It is<br/>recommended to keep this feature enabled.

### dset warden enable
 - Usage: `[p]dset warden enable <on_or_off> `

Toggles warden

### dset warden regexallowed
 - Usage: `[p]dset warden regexallowed <on_or_off> `
 - Restricted to: `BOT_OWNER`

Toggles the ability to globally create rules with user defined regex

### dset warden uploadmaxsize
 - Usage: `[p]dset warden uploadmaxsize <kilobytes> `
 - Restricted to: `BOT_OWNER`

Sets the maximum allowed size for Warden rules upload<br/><br/>Reccommended size is 3KB

### dset warden periodicallowed
 - Usage: `[p]dset warden periodicallowed <on_or_off> `
 - Restricted to: `BOT_OWNER`

Toggles the ability to globally create periodic rules<br/><br/>Periodic rules are rules that can be scheduled to run against<br/>an entire server userbase on an interval between 5 minutes and 24 hours

## dset raiderdetection
 - Usage: `[p]dset raiderdetection `
 - Restricted to: `ADMIN`
 - Aliases: `rd`

Raider detection auto module configuration<br/><br/>See [p]defender status for more information about this module

### dset raiderdetection messages
 - Usage: `[p]dset raiderdetection messages <messages> `

Sets messages (User posted X messages in Y minutes)

### dset raiderdetection wipe
 - Usage: `[p]dset raiderdetection wipe <days> `

Sets how many days worth of messages to delete if the action is ban<br/><br/>Setting 0 will not delete any message

### dset raiderdetection enable
 - Usage: `[p]dset raiderdetection enable <on_or_off> `

Toggles raider detection

### dset raiderdetection wdchecks
 - Usage: `[p]dset raiderdetection wdchecks [conditions] `

Implement advanced Warden based checks<br/><br/>Issuing this command with no arguments will show the current checks<br/>Passing 'remove' will remove existing checks

### dset raiderdetection action
 - Usage: `[p]dset raiderdetection action <action> `

Sets action (ban, kick, softban, punish or none (notify only))

### dset raiderdetection minutes
 - Usage: `[p]dset raiderdetection minutes <minutes> `

Sets minutes (User posted X messages in Y minutes)

### dset raiderdetection rank
 - Usage: `[p]dset raiderdetection rank <rank> `

Sets target rank

## dset importfrom
 - Usage: `[p]dset importfrom <server> `

Import the configuration from another server<br/><br/>This is permitted only if the command issuer is admin in both servers

## dset general
 - Usage: `[p]dset general `
 - Restricted to: `ADMIN`

Defender general settings

### dset general notifychannel
 - Usage: `[p]dset general notifychannel <channel> `

Sets the channel where notifications will be sent<br/><br/>This channel should preferably be staff readable only as it could<br/>potentially contain sensitive info

### dset general reset
 - Usage: `[p]dset general reset [confirmation=False] `

Resets Defender configuration for this server

### dset general messagecacheexpire
 - Usage: `[p]dset general messagecacheexpire <hours> `
 - Restricted to: `BOT_OWNER`

Sets how long a message should be cached before being discarded

### dset general countmessages
 - Usage: `[p]dset general countmessages <on_or_off> `

Toggles message count (and rank 4)

### dset general enable
 - Usage: `[p]dset general enable <on_or_off> `

Toggle defender system

### dset general trustedroles
 - Usage: `[p]dset general trustedroles <roles> `

Sets the trusted roles<br/><br/>Users belonging to this role will be classified as Rank 1

### dset general helperroles
 - Usage: `[p]dset general helperroles <roles> `

Sets the helper roles<br/><br/>See [p]defender status for more information about these roles

### dset general punishrole
 - Usage: `[p]dset general punishrole <role> `

Sets the role that will be assigned to misbehaving users<br/><br/>Note: this will only be assigned if the 'action' of a module<br/>is set to 'punish'.

### dset general punishmessage
 - Usage: `[p]dset general punishmessage <message> `

Sets the messages that I will send after assigning the punish role<br/><br/>Supports context variables. You can add the following to your message:<br/>$user -> User's name + tag<br/>$user_name -> User's name<br/>$user_display -> User's nickname if set or user's name<br/>$user_id -> User's id<br/>$user_mention -> User's mention<br/>$user_nickname -> User's nickname if set or 'None'

### dset general messagecachecap
 - Usage: `[p]dset general messagecachecap <messages> `
 - Restricted to: `BOT_OWNER`

Sets the maximum # of messages to cache for each user / channel

### dset general notifyrole
 - Usage: `[p]dset general notifyrole <role> `

Sets the role that will be pinged in case of alerts

## dset invitefilter
 - Usage: `[p]dset invitefilter `
 - Restricted to: `ADMIN`
 - Aliases: `if`

Invite filter auto module configuration<br/><br/>See [p]defender status for more information about this module

### dset invitefilter wdchecks
 - Usage: `[p]dset invitefilter wdchecks [conditions] `

Implement advanced Warden based checks<br/><br/>Issuing this command with no arguments will show the current checks<br/>Passing 'remove' will remove existing checks

### dset invitefilter deletemessage
 - Usage: `[p]dset invitefilter deletemessage <on_or_off> `

Toggles whether to delete the invite's message

### dset invitefilter excludeowninvites
 - Usage: `[p]dset invitefilter excludeowninvites <yes_or_no> `

Excludes this server's invites from the filter

### dset invitefilter action
 - Usage: `[p]dset invitefilter action <action> `

Sets action (ban, kick, softban, punish or none (deletion only))

### dset invitefilter enable
 - Usage: `[p]dset invitefilter enable <on_or_off> `

Toggle invite filter

### dset invitefilter rank
 - Usage: `[p]dset invitefilter rank <rank> `

Sets target rank

## dset vaporize
 - Usage: `[p]dset vaporize `
 - Restricted to: `ADMIN`

Vaporize manual module configuration<br/><br/>See [p]defender status for more information about this module

### dset vaporize maxtargets
 - Usage: `[p]dset vaporize maxtargets <max_targets> `

Sets the maximum amount of targets (1-999)<br/><br/>By default only a maximum of 15 users can be vaporized at once

### dset vaporize enable
 - Usage: `[p]dset vaporize enable <on_or_off> `

Toggle vaporize manual module

## dset rank3
 - Usage: `[p]dset rank3 `
 - Restricted to: `ADMIN`

Rank 3 configuration<br/><br/>See [p]defender status for more information about this rank

### dset rank3 minmessages
 - Usage: `[p]dset rank3 minmessages <messages> `

Minimum messages required to reach Rank 3

### dset rank3 joineddays
 - Usage: `[p]dset rank3 joineddays <days> `

Days since join required to be considered Rank 3

# defender
 - Usage: `[p]defender `
 - Restricted to: `MOD`
 - Aliases: `def`
 - Checks: `server_only`

Defender commands reserved to staff

## defender freshmeat
 - Usage: `[p]defender freshmeat [hours=24] [keywords] `

Returns a list of the new users of the day<br/><br/>Can be filtered. Supports wildcards (* and ?)

## defender warden
 - Usage: `[p]defender warden `
 - Restricted to: `ADMIN`
 - Aliases: `wd`

Warden rules management<br/><br/>See [p]defender status for more information about Warden

### defender warden exportall
 - Usage: `[p]defender warden exportall `

Sends all the rules as a tar.gz archive

### defender warden export
 - Usage: `[p]defender warden export <name> `

Sends the rule as a YAML file

### defender warden remove
 - Usage: `[p]defender warden remove <name> `

Removes a rule by name

### defender warden upload
 - Usage: `[p]defender warden upload `
 - Cooldown: `10000 per 1.0 second`

Starts a rule upload session

### defender warden find
 - Usage: `[p]defender warden find <text> `
 - Aliases: `search`

Search for text in existing rules

### defender warden add
 - Usage: `[p]defender warden add <rule> `

Adds a new rule

### defender warden show
 - Usage: `[p]defender warden show <name> `

Shows a rule

### defender warden list
 - Usage: `[p]defender warden list `

Lists existing rules

### defender warden removeall
 - Usage: `[p]defender warden removeall `

Removes all rules

### defender warden debug
 - Usage: `[p]defender warden debug <_id> <event> [rank=None] `

Simulate and give a detailed summary of an event<br/><br/>A Warden event must be passed with the proper target ID (user or local message)<br/><br/>When this command is issued all the rules registered to the event will be<br/>processed in a safe way against the target, if any.<br/>If the target satisfies the conditions, *only* the heatpoint related actions<br/>will be carried on.<br/>The heatpoint actions will be "sandboxed", so the newly added heatpoints won't<br/>have any effect outside this test.<br/>Remember that Warden evaluates each condition in order and stops at the first failed<br/>root condition: the last condition that is listed in a failed rule is where Warden<br/>stopped evaluating them.<br/>If a valid Rank is also passed it will be used in place of the target's real<br/>rank during the test.<br/>See the documentation for a full list of Warden events.<br/><br/>Example:<br/>[p]def warden debug <valid_user_id> on-user-join<br/>[p]def warden debug <valid_message_id> on-message<br/>[p]def warden debug <valid_message_id> on-message-edit 3

### defender warden memory
 - Usage: `[p]defender warden memory [keywords] `

Shows or resets the memory of Warden<br/><br/>Can be filtered. Supports wildcards (* and ?)

### defender warden run
 - Usage: `[p]defender warden run <name> `

Runs a rule against the whole userbase<br/><br/>Confirmation is asked before execution.

## defender notifynew
 - Usage: `[p]defender notifynew <hours> `

Sends you a DM if a user younger than X hours joins<br/><br/>Use 0 hours to disable notifications

## defender identify
 - Usage: `[p]defender identify <user> `

Shows a member's rank + info

## defender monitor
 - Usage: `[p]defender monitor [keywords] `

Shows recent events that might require your attention<br/><br/>Can be filtered. Supports wildcards (* and ?)

## defender memberranks
 - Usage: `[p]defender memberranks `

Counts how many members are in each rank

## defender messages
 - Usage: `[p]defender messages `
 - Aliases: `msg`

Access recorded messages of users / channels

### defender messages exportuser
 - Usage: `[p]defender messages exportuser <user> `

Exports recent messages of a user to a file

### defender messages channel
 - Usage: `[p]defender messages channel <channel> `

Shows recent messages of a channel

### defender messages exportchannel
 - Usage: `[p]defender messages exportchannel <channel> `

Exports recent messages of a channel to a file

### defender messages user
 - Usage: `[p]defender messages user <user> `

Shows recent messages of a user

## defender status
 - Usage: `[p]defender status `

Shows overall status of the Defender system

## defender updates
 - Usage: `[p]defender updates `

Shows all the past announcements of Defender

## defender emergency
 - Usage: `[p]defender emergency <on_or_off> `

Manually engage or turn off emergency mode<br/><br/>Upon activation, staff will be pinged and any module<br/>that is set to be active in emergency mode will be rendered<br/>available to helpers

# alert
 - Usage: `[p]alert `
 - Aliases: `staff`
 - Cooldown: `1 per 120.0 seconds`
 - Checks: `server_only`

Alert the staff members

# vaporize
 - Usage: `[p]vaporize <members> `
 - Checks: `server_only`

Gets rid of bad actors in a quick and silent way<br/><br/>Works only on Rank 3 and under

# voteout
 - Usage: `[p]voteout <user> `
 - Cooldown: `1 per 22.0 seconds`
 - Checks: `server_only`

Initiates a vote to expel a user from the server<br/><br/>Can be used by members with helper roles during emergency mode

# silence
 - Usage: `[p]silence <rank> `
 - Checks: `server_only`

Enables server wide message autodeletion for the specified rank (and below)<br/><br/>Passing 0 will disable this.

