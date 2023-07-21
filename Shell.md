# Shell Help

Run shell commands on bot's system from Discord.

# shell
 - Usage: `[p]shell <command> `
 - Restricted to: `BOT_OWNER`

Run shell command.

# shellq
 - Usage: `[p]shellq <command> `
 - Restricted to: `BOT_OWNER`

Run shell command quietly.<br/><br/>If command's exit code is 0, `[p]shellq` will only send a tick reaction.<br/>Otherwise, the result will be shown as with regular `[p]shell` command.

# killshells
 - Usage: `[p]killshells `
 - Restricted to: `BOT_OWNER`

Kill all shell processes started by Shell cog.

# shellset
 - Usage: `[p]shellset `
 - Restricted to: `BOT_OWNER`

Manage settings of the Shell cog.

## shellset shell
 - Usage: `[p]shellset shell <replacement_shell> `

Set a replacement shell for the default ``/bin/sh``.<br/><br/>This needs to be a full path to the replacement shell.<br/>The input is not validated.<br/><br/>Only works on POSIX systems.

### shellset shell reset
 - Usage: `[p]shellset shell reset `

Reset the replacement shell back to the default.

