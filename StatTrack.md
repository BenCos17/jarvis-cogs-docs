# StatTrack Help

Track your bot's metrics and view them in Discord.<br/>This cog creates its own SQLite database to store data, using around 150KB per day.<br/><br/>Commands will output as a graph.<br/>Data can also be exported with `[p]stattrack export` into a few different formats.

# stattrack
 - Usage: `[p]stattrack `
 - Cooldown: `10 per 60.0 seconds`

View my stats.

## stattrack servers
 - Usage: `[p]stattrack servers [timespan=1 day, 0:00:00] `
 - Aliases: `servers`

Get server stats.<br/><br/>**Arguments**<br/><br/>`<timespan>` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack servers 3w2d`<br/>- `[p]stattrack servers 5d`<br/>- `[p]stattrack servers all`

## stattrack status
 - Usage: `[p]stattrack status [timespan=1 day, 0:00:00] <metrics> `

Get status stats.<br/><br/>You can just run this command on its own to see all metrics,<br/>or specify some metrics - see below.<br/><br/>**Arguments**<br/><br/>`[timespan]` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>`[metrics]` The metrics to show. Valid options: `online`, `idle`, `offline`, `dnd`.<br/>Defaults to all of them.<br/><br/>**Examples:**<br/>- `[p]stattrack status` - show all metrics, 1 day<br/>- `[p]stattrack status 3w2d` - show all metrics, 3 weeks 2 days<br/>- `[p]stattrack status 5d dnd online` - show dnd & online, 5 days<br/>- `[p]stattrack status all online idle` - show online & idle, all time

## stattrack users
 - Usage: `[p]stattrack users [timespan=1 day, 0:00:00] <metrics> `

Get user stats.<br/><br/>You can just run this command on its own to see all metrics,<br/>or specify some metrics - see below.<br/><br/>**Arguments**<br/><br/>`[timespan]` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>`[metrics]` The metrics to show. Valid options: `total`, `unique`, `humans`, `bots`.<br/>Defaults to all of them.<br/><br/>Note that `total` will count users multiple times if they share multiple servers with the<br/>[botname], while `unique` will only count them once.<br/><br/>**Examples:**<br/>- `[p]stattrack users` - show all metrics, 1 day<br/>- `[p]stattrack users 3w2d` - show all metrics, 3 weeks 2 days<br/>- `[p]stattrack users 5d total unique` - show total & unique, 5 days<br/>- `[p]stattrack users all humans bots` - show humans & bots, all time

## stattrack latency
 - Usage: `[p]stattrack latency [timespan=1 day, 0:00:00] `
 - Aliases: `ping`

Get my latency stats.<br/><br/>**Arguments**<br/><br/>`<timespan>` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack latency 3w2d`<br/>- `[p]stattrack latency 5d`<br/>- `[p]stattrack latency all`

## stattrack channels
 - Usage: `[p]stattrack channels [timespan=1 day, 0:00:00] <metrics> `

Get channel stats.<br/><br/>You can just run this command on its own to see all metrics,<br/>or specify some metrics - see below.<br/><br/>**Arguments**<br/><br/>`[timespan]` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>`[metrics]` The metrics to show.<br/>Valid options: `total`, `text`, `voice`, `stage`, `category`.<br/>Defaults to all of them.<br/><br/>Note that `total` will count users multiple times if they share multiple servers with the<br/>[botname], while `unique` will only count them once.<br/><br/>**Examples:**<br/>**Examples:**<br/>- `[p]stattrack servers 3w2d`<br/>- `[p]stattrack servers 5d`<br/>- `[p]stattrack servers all`

## stattrack messages
 - Usage: `[p]stattrack messages [timespan=1 day, 0:00:00] `

Get message stats.<br/><br/>**Arguments**<br/><br/>`<timespan>` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack messages 3w2d`<br/>- `[p]stattrack messages 5d`<br/>- `[p]stattrack messages all`

## stattrack looptime
 - Usage: `[p]stattrack looptime [timespan=1 day, 0:00:00] `
 - Aliases: `time and loop`

Get my loop time stats.<br/><br/>**Arguments**<br/><br/>`<timespan>` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack looptime 3w2d`<br/>- `[p]stattrack looptime 5d`<br/>- `[p]stattrack looptime all`

## stattrack commands
 - Usage: `[p]stattrack commands [timespan=1 day, 0:00:00] `

Get command usage stats.<br/><br/>**Arguments**<br/><br/>`<timespan>` How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack commands 3w2d`<br/>- `[p]stattrack commands 5d`<br/>- `[p]stattrack commands all`

## stattrack system
 - Usage: `[p]stattrack system `
 - Aliases: `sys`

Get system metrics.

### stattrack system mem
 - Usage: `[p]stattrack system mem [timespan=1 day, 0:00:00] `
 - Aliases: `memory and ram`

Get memory usage stats.<br/><br/>**Arguments**<br/><br/><timespan> How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack system mem 3w2d`<br/>- `[p]stattrack system mem 5d`<br/>- `[p]stattrack system mem all`

### stattrack system cpu
 - Usage: `[p]stattrack system cpu [timespan=1 day, 0:00:00] `

Get CPU stats.<br/><br/>**Arguments**<br/><br/><timespan> How long to look for, or `all` for all-time data. Defaults to 1 day. Must be<br/>at least 1 hour.<br/><br/>**Examples:**<br/>- `[p]stattrack system cpu 3w2d`<br/>- `[p]stattrack system cpu 5d`<br/>- `[p]stattrack system cpu all`

## stattrack maxpoints
 - Usage: `[p]stattrack maxpoints <maxpoints> `
 - Restricted to: `BOT_OWNER`

Set the maximum number of points to plot. This affects the speed of graph plotting.<br/><br/>The default value is 25k (25000).<br/><br/>The more points you plot, the slower the plotting time will be.<br/><br/>This setting only affects graphs that are a longer timespan (1 month+).<br/><br/>Set maxpoints to -1 to disable this feature, therefore always plotting all points.<br/><br/>Otherwise, maxpoints must be at least 1k (1440).<br/><br/>**Examples:**<br/>- `[p]stattrack maxpoints 10000` - plot up to 10k points<br/>- `[p]stattrack maxpoints 75000` - plot up to 75k points<br/>- `[p]stattrack maxpoints 1440` - the minimum value possible<br/>- `[p]stattrack maxpoints 25000` - the default value<br/>- `[p]stattrack maxpoints -1` - disable, always plot all points

## stattrack export
 - Usage: `[p]stattrack export `
 - Restricted to: `BOT_OWNER`

Export stattrack data.

### stattrack export csv
 - Usage: `[p]stattrack export csv `

Export as CSV

### stattrack export json
 - Usage: `[p]stattrack export json `

Export as JSON with pandas orient "split" 

