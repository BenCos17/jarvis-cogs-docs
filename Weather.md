# Weather Help

Get weather data from https://openweathermap.org

# weather (Hybrid Command)
 - Usage: `[p]weather <forecast> <units> <search> `
 - Slash Usage: `/weather <forecast> <units> <search> `
 - Aliases: `we`

Display weather in a given location<br/><br/>`search` must take the form of `city, state, Country Code`<br/>example: `[p]weather New York, New York, US`

## weather coords (Hybrid Command)
 - Usage: `[p]weather coords <forecast> <units> <lat> <lon> `
 - Slash Usage: `/weather coords <forecast> <units> <lat> <lon> `
 - Aliases: `co and coordinates`

Display weather in a given location<br/><br/>`lat` and `lon` specify a precise point on Earth using the<br/>geographic coordinates specified by latitude (north-south) and longitude (east-west).<br/>example: `[p]weather coordinates 35 139`

## weather set (Hybrid Command)
 - Usage: `[p]weather set `
 - Slash Usage: `/weather set `

Set user or server default units

### weather set bot (Hybrid Command)
 - Usage: `[p]weather set bot <units> `
 - Slash Usage: `/weather set bot <units> `
 - Restricted to: `MOD`

Sets the bots default weather units<br/><br/>`units` must be one of imperial, metric, or standard (kelvin)

### weather set creds (Hybrid Command)
 - Usage: `[p]weather set creds `
 - Slash Usage: `/weather set creds `
 - Restricted to: `BOT_OWNER`

How to setup the weather cog credentials<br/><br/>1. go to https://openweathermap.org<br/>2. Create an account.<br/>3. go to https://home.openweathermap.org/api_keys<br/>4. Enter an API key name and click Generate<br/>5. Copy the key and run `[p]set api openweathermap api_key YOUR_API_KEY_HERE`<br/>6. go to https://home.openweathermap.org/subscriptions and Subscribe to One Call by Call

### weather set server (Hybrid Command)
 - Usage: `[p]weather set server <units> `
 - Slash Usage: `/weather set server <units> `
 - Restricted to: `MOD`
 - Aliases: `server`
 - Checks: `server_only`

Sets the server default weather units<br/><br/>`units` must be one of imperial, metric, or standard (kelvin)

### weather set user (Hybrid Command)
 - Usage: `[p]weather set user <units> `
 - Slash Usage: `/weather set user <units> `

Sets the user default weather units<br/><br/>`units` must be one of imperial, metric, or standard (kelvin)<br/>Note: User settings override server settings.

## weather zip (Hybrid Command)
 - Usage: `[p]weather zip <forecast> <units> <zipcode> `
 - Slash Usage: `/weather zip <forecast> <units> <zipcode> `

Display weather in a given location<br/><br/>`zipcode` must be a valid ZIP code or `ZIP code, Country Code` (assumes US otherwise)<br/>example: `[p]weather zip 20500`

