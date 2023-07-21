# Mcsvr Help

Get info about a Minecraft server.<br/><br/>This only supports Java edition servers at this time.<br/><br/>Also available is a server tracker that allows displaying a server and<br/>automatically updating its information while the cog is loaded.

# mcserver
 - Usage: `[p]mcserver <server_ip> `

Display info about the specified server<br/><br/>Server type must either be 'Java' or 'Bedrock'

# addserver
 - Usage: `[p]addserver <server_ip> [channel=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Set a server to track.<br/><br/>The server info will be used for the channel's description.

# delserver
 - Usage: `[p]delserver [server_ip=None] [channel=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Removes a server from the tracker

# mcset
 - Usage: `[p]mcset `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Settings for the server tracker

## mcset mode
 - Usage: `[p]mcset mode <mode> [confirm=False] `

Sets the server tracker mode for the server.<br/><br/>Valid values for the mode param are `text` or `embed`.<br/>If set to embed, multiple servers can be tracked in one channel.<br/>If set to text, only one server is allowed per channel because<br/>the channel topic will be used for the display.

