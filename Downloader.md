# Downloader Help

Install community cogs made by Cog Creators.<br/><br/>Community cogs, also called third party cogs, are not included<br/>in the default Red install.<br/><br/>Community cogs come in repositories. Repos are a group of cogs<br/>you can install. You always need to add the creator's repository<br/>using the `[p]repo` command before you can install one or more<br/>cogs from the creator.

# pipinstall
 - Usage: `[p]pipinstall <deps> `
 - Restricted to: `BOT_OWNER`

Install a group of dependencies using pip.<br/><br/>Examples:<br/>- `[p]pipinstall bs4`<br/>- `[p]pipinstall py-cpuinfo psutil`<br/><br/>Improper usage of this command can break your bot, be careful.<br/><br/>**Arguments**<br/><br/>- `<deps...>` The package or packages you wish to install.

# repo
 - Usage: `[p]repo `
 - Restricted to: `BOT_OWNER`

Base command for repository management.

## repo add
 - Usage: `[p]repo add <name> <repo_url> [branch=None] `

Add a new repo.<br/><br/>Examples:<br/>- `[p]repo add 26-Cogs https://github.com/Twentysix26/x26-Cogs`<br/>- `[p]repo add Laggrons-Dumb-Cogs https://github.com/retke/Laggrons-Dumb-Cogs v3`<br/><br/>Repo names can only contain characters A-z, numbers, underscores, hyphens, and dots (but they cannot start or end with a dot).<br/><br/>The branch will be the default branch if not specified.<br/><br/>**Arguments**<br/><br/>- `<name>` The name given to the repo.<br/>- `<repo_url>` URL to the cog branch. Usually GitHub or GitLab.<br/>- `[branch]` Optional branch to install cogs from.

## repo delete
 - Usage: `[p]repo delete <repos> `
 - Aliases: `remove and del`

Remove repos and their files.<br/><br/>Examples:<br/>- `[p]repo delete 26-Cogs`<br/>- `[p]repo delete 26-Cogs Laggrons-Dumb-Cogs`<br/><br/>**Arguments**<br/><br/>- `<repos...>` The repo or repos to remove.

## repo list
 - Usage: `[p]repo list `

List all installed repos.

## repo info
 - Usage: `[p]repo info <repo> `

Show information about a repo.<br/><br/>Example:<br/>- `[p]repo info 26-Cogs`<br/><br/>**Arguments**<br/><br/>- `<repo>` The name of the repo to show info about.

## repo update
 - Usage: `[p]repo update <repos> `

Update all repos, or ones of your choosing.<br/><br/>This will *not* update the cogs installed from those repos.<br/><br/>Examples:<br/>- `[p]repo update`<br/>- `[p]repo update 26-Cogs`<br/>- `[p]repo update 26-Cogs Laggrons-Dumb-Cogs`<br/><br/>**Arguments**<br/><br/>- `[repos...]` The name or names of repos to update. If omitted, all repos are updated.

# cog
 - Usage: `[p]cog `
 - Restricted to: `BOT_OWNER`

Base command for cog installation management commands.

## cog unpin
 - Usage: `[p]cog unpin <cogs> `

Unpin cogs - this will remove the update lock from those cogs.<br/><br/>Examples:<br/>- `[p]cog unpin defender`<br/>- `[p]cog unpin updated_cog1 updated_cog2`<br/><br/>**Arguments**<br/><br/>- `<cogs...>` The cog or cogs to unpin. Must already be installed and pinned.

## cog info
 - Usage: `[p]cog info <repo> <cog_name> `

List information about a single cog.<br/><br/>Example:<br/>- `[p]cog info 26-Cogs defender`<br/><br/>**Arguments**<br/><br/>- `<repo>` The repo to get cog info from.<br/>- `<cog>` The cog to get info on.

## cog install
 - Usage: `[p]cog install <repo> <cog_names> `

Install a cog from the given repo.<br/><br/>Examples:<br/>- `[p]cog install 26-Cogs defender`<br/>- `[p]cog install Laggrons-Dumb-Cogs say roleinvite`<br/><br/>**Arguments**<br/><br/>- `<repo>` The name of the repo to install cogs from.<br/>- `<cogs...>` The cog or cogs to install.

## cog checkforupdates
 - Usage: `[p]cog checkforupdates `

Check for available cog updates (including pinned cogs).<br/><br/>This command doesn't update cogs, it only checks for updates.<br/>Use `[p]cog update` to update cogs.

## cog list
 - Usage: `[p]cog list <repo> `

List all available cogs from a single repo.<br/><br/>Example:<br/>- `[p]cog list 26-Cogs`<br/><br/>**Arguments**<br/><br/>- `<repo>` The repo to list cogs from.

## cog pin
 - Usage: `[p]cog pin <cogs> `

Pin cogs - this will lock cogs on their current version.<br/><br/>Examples:<br/>- `[p]cog pin defender`<br/>- `[p]cog pin outdated_cog1 outdated_cog2`<br/><br/>**Arguments**<br/><br/>- `<cogs...>` The cog or cogs to pin. Must already be installed.

## cog update
 - Usage: `[p]cog update <reload> <cogs> `

Update all cogs, or ones of your choosing.<br/><br/>Examples:<br/>- `[p]cog update`<br/>- `[p]cog update True`<br/>- `[p]cog update defender`<br/>- `[p]cog update True defender`<br/><br/>**Arguments**<br/><br/>- `[reload]` Whether to reload cogs immediately after update or not.<br/>- `[cogs...]` The cog or cogs to update. If omitted, all cogs are updated.

## cog updatetoversion
 - Usage: `[p]cog updatetoversion <reload> <repo> <revision> <cogs> `

Update all cogs, or ones of your choosing to chosen revision of one repo.<br/><br/>Note that update doesn't mean downgrade and therefore `revision`<br/>has to be newer than the version that cog currently has installed. If you want to<br/>downgrade the cog, uninstall and install it again.<br/><br/>See `[p]cog installversion` for an explanation of `revision`.<br/><br/>Examples:<br/>- `[p]cog updatetoversion Broken-Repo e798cc268e199612b1316a3d1f193da0770c7016 cog_name`<br/>- `[p]cog updatetoversion True Broken-Repo 6107c0770ad391f1d3a6131b216991e862cc897e cog_name`<br/><br/>**Arguments**<br/><br/>- `[reload]` Whether to reload cogs immediately after update or not.<br/>- `<repo>` The repo or repos to update all cogs from.<br/>- `<revision>` The revision to update to.<br/>- `[cogs...]` The cog or cogs to update.

## cog installversion
 - Usage: `[p]cog installversion <repo> <revision> <cog_names> `

Install a cog from the specified revision of given repo.<br/><br/>Revisions are "commit ids" that point to the point in the code when a specific change was made.<br/>The latest revision can be found in the URL bar for any GitHub repo by [pressing "y" on that repo](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/getting-permanent-links-to-files#press-y-to-permalink-to-a-file-in-a-specific-commit).<br/><br/>Older revisions can be found in the URL bar by [viewing the commit history of any repo](https://cdn.discordapp.com/attachments/133251234164375552/775760247787749406/unknown.png)<br/><br/>Example:<br/>- `[p]cog installversion Broken-Repo e798cc268e199612b1316a3d1f193da0770c7016 cog_name`<br/><br/>**Arguments**<br/><br/>- `<repo>` The name of the repo to install cogs from.<br/>- `<revision>` The revision to install from.<br/>- `<cogs...>` The cog or cogs to install.

## cog uninstall
 - Usage: `[p]cog uninstall <cogs> `

Uninstall cogs.<br/><br/>You may only uninstall cogs which were previously installed<br/>by Downloader.<br/><br/>Examples:<br/>- `[p]cog uninstall defender`<br/>- `[p]cog uninstall say roleinvite`<br/><br/>**Arguments**<br/><br/>- `<cogs...>` The cog or cogs to uninstall.

## cog listpinned
 - Usage: `[p]cog listpinned `

List currently pinned cogs.

## cog updateallfromrepos
 - Usage: `[p]cog updateallfromrepos <reload> <repos> `

Update all cogs from repos of your choosing.<br/><br/>Examples:<br/>- `[p]cog updateallfromrepos 26-Cogs`<br/>- `[p]cog updateallfromrepos True 26-Cogs`<br/>- `[p]cog updateallfromrepos Laggrons-Dumb-Cogs 26-Cogs`<br/><br/>**Arguments**<br/><br/>- `[reload]` Whether to reload cogs immediately after update or not.<br/>- `<repos...>` The repo or repos to update all cogs from.

# findcog
 - Usage: `[p]findcog <command_name> `

Find which cog a command comes from.<br/><br/>This will only work with loaded cogs.<br/><br/>Example:<br/>- `[p]findcog ping`<br/><br/>**Arguments**<br/><br/>- `<command_name>` The command to search for.

