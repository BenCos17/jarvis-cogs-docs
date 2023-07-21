# PayDay Help

Customizable PayDay system<br/><br/>More detailed docs: <https://cogs.yamikaitou.dev/payday.html>

# freecredits
 - Usage: `[p]freecredits `
 - Checks: `server_only_check`

More options to get free credits

## freecredits times
 - Usage: `[p]freecredits times `
 - Checks: `cmd_all`

Display remaining time for all options

## freecredits daily
 - Usage: `[p]freecredits daily `
 - Checks: `cmd_check`

Get some free currency every day

## freecredits all
 - Usage: `[p]freecredits all `
 - Checks: `cmd_all`

Claim all available freecredits

## freecredits monthly
 - Usage: `[p]freecredits monthly `
 - Checks: `cmd_check`

Get some free currency every month (30 days)

## freecredits hourly
 - Usage: `[p]freecredits hourly `
 - Checks: `cmd_check`

Get some free currency every hour

## freecredits quarterly
 - Usage: `[p]freecredits quarterly `
 - Checks: `cmd_check`

Get some free currency every quarter (122 days)

## freecredits yearly
 - Usage: `[p]freecredits yearly `
 - Checks: `cmd_check`

Get some free currency every year (365 days)

## freecredits weekly
 - Usage: `[p]freecredits weekly `
 - Checks: `cmd_check`

Get some free currency every week (7 days)

# pdconfig
 - Usage: `[p]pdconfig `
 - Restricted to: `GUILD_OWNER`
 - Checks: `is_owner_if_bank_global`

Configure the `freecredits` options<br/><br/>More detailed docs: <https://cogs.yamikaitou.dev/payday.html#pdconfig>

## pdconfig settings
 - Usage: `[p]pdconfig settings `
 - Restricted to: `GUILD_OWNER`
 - Checks: `is_owner_if_bank_global`

Print the `freecredits` options

## pdconfig monthly
 - Usage: `[p]pdconfig monthly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `month`
 - Checks: `is_owner_if_bank_global`

Configure the `monthly` options<br/><br/>Setting this to 0 will disable the command

## pdconfig weekly
 - Usage: `[p]pdconfig weekly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `week`
 - Checks: `is_owner_if_bank_global`

Configure the `weekly` options<br/><br/>Setting this to 0 will disable the command

## pdconfig yearly
 - Usage: `[p]pdconfig yearly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `year`
 - Checks: `is_owner_if_bank_global`

Configure the `yearly` options<br/><br/>Setting this to 0 will disable the command

## pdconfig streaks
 - Usage: `[p]pdconfig streaks `
 - Restricted to: `GUILD_OWNER`
 - Checks: `is_owner_if_bank_global`

Configure the `streaks` options

### pdconfig streaks hourly
 - Usage: `[p]pdconfig streaks hourly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `hour`
 - Checks: `is_owner_if_bank_global`

Configure the `hourly` streaks value<br/><br/>Setting this to 0 will disable the streak bonus

### pdconfig streaks monthly
 - Usage: `[p]pdconfig streaks monthly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `month`
 - Checks: `is_owner_if_bank_global`

Configure the `monthly` streaks value<br/><br/>Setting this to 0 will disable the streak bonus

### pdconfig streaks quarterly
 - Usage: `[p]pdconfig streaks quarterly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `quarter`
 - Checks: `is_owner_if_bank_global`

Configure the `quarterly` streaks value<br/><br/>Setting this to 0 will disable the streak bonus

### pdconfig streaks yearly
 - Usage: `[p]pdconfig streaks yearly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `year`
 - Checks: `is_owner_if_bank_global`

Configure the `yearly` streaks value<br/><br/>Setting this to 0 will disable the streak bonus

### pdconfig streaks weekly
 - Usage: `[p]pdconfig streaks weekly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `week`
 - Checks: `is_owner_if_bank_global`

Configure the `weekly` streaks value<br/><br/>Setting this to 0 will disable the streak bonus

### pdconfig streaks daily
 - Usage: `[p]pdconfig streaks daily <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `day`
 - Checks: `is_owner_if_bank_global`

Configure the `daily` streaks value<br/><br/>Setting this to 0 will disable the streak bonus

### pdconfig streaks percent
 - Usage: `[p]pdconfig streaks percent <state> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `percentage`
 - Checks: `is_owner_if_bank_global`

Configure streaks to be a percentage or flat amount<br/><br/><state> should be any of these combinations, `on/off`, `yes/no`, `1/0`, `true/false`

## pdconfig hourly
 - Usage: `[p]pdconfig hourly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `hour`
 - Checks: `is_owner_if_bank_global`

Configure the `hourly` options<br/><br/>Setting this to 0 will disable the command

## pdconfig daily
 - Usage: `[p]pdconfig daily <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `day`
 - Checks: `is_owner_if_bank_global`

Configure the `daily` options<br/><br/>Setting this to 0 will disable the command

## pdconfig quarterly
 - Usage: `[p]pdconfig quarterly <value> `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `quarter`
 - Checks: `is_owner_if_bank_global`

Configure the `quarterly` options<br/><br/>Setting this to 0 will disable the command

