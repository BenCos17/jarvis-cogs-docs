# AnotherPingCog Help

A rich embed ping command with latency timings.<br/><br/>You can customise the emojis, colours or force embeds with `[p]pingset`.

# ping (Hybrid Command)
 - Usage: `[p]ping `
 - Slash Usage: `/ping `
 - Aliases: `pinf, pig, png, pign, pjgn, ipng, pgn and pnig`

A rich embed ping command with timings.<br/><br/>This will show the time to send a message, and the WS latency to Discord.<br/>If I can't send embeds or they are disabled here, I will send a normal message instead.<br/>The embed has more detail and is preferred.

# pingset
 - Usage: `[p]pingset `
 - Restricted to: `BOT_OWNER`

Manage settings - emojis, embed colour, and force embed.

## pingset orange
 - Usage: `[p]pingset orange <emoji> [hex_colour=default] `

Set the colour and emoji to use for the colour Orange.<br/><br/>If you want to go back to the defaults, just do `[p]pingset orange default default`.<br/><br/>**Arguments:**<br/>    `<emoji>`<br/>    Just send the emoji as you normally would. It must be a custom emoji and I must<br/>    be in the sever the emoji is in.<br/>    You can also put `default` to use 🟠<br/><br/>    `[hex_colour]` (optional)<br/>    The hex code you want the colour for Red to be. It looks best when this is the<br/>    same colour as the emoji. Google "hex colour" if you need help with this.<br/><br/>**Examples:**<br/>- `[p]pingset orange :emoji: #FAA61A`<br/>- `[p]pingset orange :emoji: default`<br/>- `[p]pingset orange default #FAA61A`<br/>- `[p]pingset orange default default`

## pingset footer
 - Usage: `[p]pingset footer <text> `

Set a custom footer for the ping embed.<br/><br/>If `none` is provided as the parameter, there will be no embed footer.<br/><br/>If `default` is provided as the parameter, the default footer will be used.<br/><br/>Otherwise, the provided text will be used as the custom footer.

## pingset red
 - Usage: `[p]pingset red <emoji> [hex_colour=default] `

Set the colour and emoji to use for the colour Red.<br/><br/>If you want to go back to the defaults, just do `[p]pingset red default default`.<br/><br/>**Arguments:**<br/>    `<emoji>`<br/>    Just send the emoji as you normally would. It must be a custom emoji and I must<br/>    be in the sever the emoji is in.<br/>    You can also put `default` to use 🔴<br/><br/>    `[hex_colour]` (optional)<br/>    The hex code you want the colour for Red to be. It looks best when this is the<br/>    same colour as the emoji. Google "hex colour" if you need help with this.<br/><br/>**Examples:**<br/>- `[p]pingset red :emoji: #F04747`<br/>- `[p]pingset red :emoji: default`<br/>- `[p]pingset red default #F04747`<br/>- `[p]pingset red default default`

## pingset settings
 - Usage: `[p]pingset settings `

See your current settings.

## pingset forceembed
 - Usage: `[p]pingset forceembed `

Toggle whether embeds should be forced.<br/><br/>If this is disabled, embeds will depend on the settings in `embedset`.<br/><br/>If it's enabled, embeds will embeds will always be sent unless the bot doesn't<br/>have permission to send them.<br/><br/>By default, this is True because the embed is richer and has more information.<br/>And it looks looks better.<br/><br/>This will be removed when a global per-command settings is available in Core Red.

## pingset green
 - Usage: `[p]pingset green <emoji> [hex_colour=default] `

Set the colour and emoji to use for the colour Green.<br/><br/>If you want to go back to the defaults, just do `[p]pingset green default default`.<br/><br/>**Arguments:**<br/>    `<emoji>`<br/>    Just send the emoji as you normally would. It must be a custom emoji and I must<br/>    be in the sever the emoji is in.<br/>    You can also put `default` to use 🟢<br/><br/>    `[hex_colour]` (optional)<br/>    The hex code you want the colour for Red to be. It looks best when this is the<br/>    same colour as the emoji. Google "hex colour" if you need help with this.<br/><br/>**Examples:**<br/>- `[p]pingset green :emoji: #43B581`<br/>- `[p]pingset green :emoji: default`<br/>- `[p]pingset green default #43B581`<br/>- `[p]pingset green default default`

