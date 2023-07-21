# PartyGames Help

Chat games focused on coming up with words from 3 letters.

# partygames
 - Usage: `[p]partygames `
 - Aliases: `pg`

Group command for party games.

## partygames mix
 - Usage: `[p]partygames mix [maxpoints=5] `

Play a mixture of all 4 games.<br/><br/>Words cannot be reused.<br/>The first person to get `maxpoints` points wins.

## partygames long
 - Usage: `[p]partygames long [maxpoints=5] `

Type the longest word.<br/><br/>The person to type the longest word that contains the given characters gets a point.<br/>Words cannot be reused.<br/>The first person to get `maxpoints` points wins.

## partygames bombparty
 - Usage: `[p]partygames bombparty [hp=3] `

Start a game of bombparty.<br/><br/>Each player will be asked to come up with a word that contains the given characters.<br/>If they are unable to do so, they will lose a life.<br/>Words cannot be reused.<br/>The last person to have lives left wins.

## partygames most
 - Usage: `[p]partygames most [maxpoints=5] `

Type the most words.<br/><br/>The person to type the most words that contain the given characters gets a point.<br/>Words cannot be reused.<br/>The first person to get `maxpoints` points wins.

## partygames fast
 - Usage: `[p]partygames fast [maxpoints=5] `

Race to type a word the fastest.<br/><br/>The first person to type a word that contains the given characters gets a point.<br/>Words cannot be reused.<br/>The first person to get `maxpoints` points wins.<br/>                

# partygamesset
 - Usage: `[p]partygamesset `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `pgset`

Config options for partygames.

## partygamesset fasttime
 - Usage: `[p]partygamesset fasttime [value=None] `

Set the timeout of fast.<br/><br/>Defaults to 15.<br/>This value is server specific.

## partygamesset mosttime
 - Usage: `[p]partygamesset mosttime [value=None] `

Set the timeout of most.<br/><br/>Defaults to 15.<br/>This value is server specific.

## partygamesset longtime
 - Usage: `[p]partygamesset longtime [value=None] `

Set the timeout of long.<br/><br/>Defaults to 15.<br/>This value is server specific.<br/>                

## partygamesset bombtime
 - Usage: `[p]partygamesset bombtime [value=None] `

Set the timeout of bombparty.<br/><br/>Defaults to 7.<br/>This value is server specific.

## partygamesset locale
 - Usage: `[p]partygamesset locale <locale> `

Override the bot's locale for partygames.<br/><br/>Defaults to None.<br/>This value is server specific.<br/>                

### partygamesset locale remove
 - Usage: `[p]partygamesset locale remove `

Remove the locale override and use the bot's locale.<br/>                

