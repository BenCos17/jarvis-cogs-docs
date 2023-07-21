# Hangman Help

Play hangman with the bot.

# hangman
 - Usage: `[p]hangman `

Play hangman with the bot.

# hangmanset
 - Usage: `[p]hangmanset `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Config options for hangman.

## hangmanset wordlist
 - Usage: `[p]hangmanset wordlist <value> `

Change the wordlist used.<br/><br/>Extra wordlists can be put in the data folder.<br/>Wordlists are a .txt file with every new line being a new word.<br/>This value is server specific.

### hangmanset wordlist list
 - Usage: `[p]hangmanset wordlist list `

List available wordlists.

### hangmanset wordlist default
 - Usage: `[p]hangmanset wordlist default `

Set the wordlist to the default list.

### hangmanset wordlist current
 - Usage: `[p]hangmanset wordlist current `

Show the current wordlist.

## hangmanset edit
 - Usage: `[p]hangmanset edit [value=None] `

Set if hangman messages should be one edited message or many individual messages.<br/><br/>Defaults to True.<br/>This value is server specific.

