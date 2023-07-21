# Prefix Help

Prefix management.

# prefix
 - Usage: `[p]prefix `
 - Checks: `server_only`

Manage server prefixes.<br/><br/>Running this command without subcommands will show this server's prefixes.<br/><br/>**Example:**<br/>`[p]prefix`

## prefix set
 - Usage: `[p]prefix set <prefixes> `
 - Restricted to: `ADMIN`
 - Aliases: `=`

Set the prefixes for this server.<br/><br/>Multiple prefixes can be set at once.<br/>To add a prefix with spaces, use quotes.<br/>This will overwrite any current prefixes.<br/><br/>**Examples:**<br/>`[p]prefix set ! n!`<br/>`[p]prefix set .. & "Hey siri, "`

## prefix clear
 - Usage: `[p]prefix clear `
 - Restricted to: `ADMIN`
 - Aliases: `reset`

Reset this server's prefixes to the default list.<br/><br/>This cannot be undone.<br/><br/>**Example:**<br/>`[p]prefix clear`

## prefix remove
 - Usage: `[p]prefix remove <prefix> `
 - Restricted to: `ADMIN`
 - Aliases: `-`

Remove a prefix from this server's prefix list.<br/><br/>Use quotes to remove a prefix with spaces.<br/><br/>**Examples:**<br/>`[p]prefix remove ~`<br/>`[p]prefix - "Alexa, "`

## prefix add
 - Usage: `[p]prefix add <prefix> `
 - Restricted to: `ADMIN`
 - Aliases: `+`

Add a prefix to this server's prefix list.<br/><br/>Use quotes to add a prefix with spaces.<br/><br/>**Examples:**<br/>`[p]prefix add ?`<br/>`[p]prefix + "[botname], can you please "`

