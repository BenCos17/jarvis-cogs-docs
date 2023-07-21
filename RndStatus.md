# RndStatus Help

Cycles random statuses or displays bot stats.<br/>If a custom status is already set, it won't change it until<br/>it's back to none. [p]set game

# rndstatus
 - Usage: `[p]rndstatus `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Rndstatus group commands.

## rndstatus delay
 - Usage: `[p]rndstatus delay <seconds> `

Sets interval of random status switch.<br/>Must be 20 or superior.

## rndstatus type
 - Usage: `[p]rndstatus type <status_type> `

Define the rndstatus game type.<br/><br/>Type list:<br/>0 = Playing<br/>1 = Streaming<br/>2 = Listening<br/>3 = Watching<br/>5 = Competing

## rndstatus status
 - Usage: `[p]rndstatus status <status> `

Define the rndstatus presence status.<br/><br/>Status list:<br/>0 = Online<br/>1 = Idle<br/>2 = DND<br/>3 = Invisible

## rndstatus set
 - Usage: `[p]rndstatus set <statuses> `

Sets Red's random statuses.<br/>Accepts multiple statuses.<br/>Must be enclosed in double quotes in case of multiple words.<br/>Example:<br/>[p]rndstatus set "Tomb Raider II" "Transistor" "with your heart."<br/>Shows current list if empty.

## rndstatus streamer
 - Usage: `[p]rndstatus streamer [streamer] `

Set the streamer name needed for streaming statuses.

## rndstatus botstats
 - Usage: `[p]rndstatus botstats <statuses> `

Toggle for a bot stats status instead of random messages.

