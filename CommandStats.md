# CommandStats Help

Command Statistics.

# cmd
 - Usage: `[p]cmd [command] `
 - Restricted to: `BOT_OWNER`

Group command for command stats.<br/><br/>This command does not log the issuing command.

## cmd server
 - Usage: `[p]cmd server [server=None] [command] `
 - Aliases: `server`

Guild Command Stats.

## cmd session
 - Usage: `[p]cmd session [command] `

Session command stats.

## cmd cogstats
 - Usage: `[p]cmd cogstats [cogname] `

Show command stats per cog, all cogs or per session.

### cmd cogstats session
 - Usage: `[p]cmd cogstats session [cogname] `

Cog stats in this session.

## cmd servers
 - Usage: `[p]cmd servers `
 - Restricted to: `BOT_OWNER`

Leaderboard of servers by most commands used.

## cmd automated
 - Usage: `[p]cmd automated `

Automated command stats.<br/><br/>Commands that have `ctx.assume_yes` will qualify as automated.

## cmd repo
 - Usage: `[p]cmd repo [repo=None] `
 - Restricted to: `BOT_OWNER`
 - Checks: `downloadercheck`

Show command stats per Repo or by repo.

## cmd csv
 - Usage: `[p]cmd csv `

Return a CSV of all command actions.

## cmd search
 - Usage: `[p]cmd search <command> `

Search for command stats

