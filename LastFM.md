# LastFM Help

Interacts with the last.fm API.

# whoknows
 - Usage: `[p]whoknows [artistname] `
 - Aliases: `wk`
 - Cooldown: `2 per 10.0 seconds`
 - Checks: `server_only and tokencheck`

Check who has listened to a given artist the most.

# whoknowstrack
 - Usage: `[p]whoknowstrack [track] `
 - Aliases: `wkt and whoknowst`
 - Cooldown: `2 per 15.0 seconds`
 - Checks: `server_only and tokencheck`

Check who has listened to a given song the most.

# whoknowsalbum
 - Usage: `[p]whoknowsalbum [album] `
 - Aliases: `wka and whoknowsa`
 - Cooldown: `2 per 15.0 seconds`
 - Checks: `server_only and tokencheck`

Check who has listened to a given album the most.

# scrobble
 - Usage: `[p]scrobble <track> `
 - Cooldown: `1 per 300.0 seconds`

Scrobble a song to last.fm.<br/><br/>Usage:<br/>    [p]scrobble <track name> | <artist name>

# fm
 - Usage: `[p]fm `
 - Checks: `tokencheck`

LastFM commands

## fm loved
 - Usage: `[p]fm loved [user=None] `

Get a list of loved songs for a user.<br/><br/>Usage:<br/>    [p]loved<br/>    [p]loved <user>

## fm artist
 - Usage: `[p]fm artist <timeframe> <datatype> [artistname] `

Your top tracks or albums for specific artist.<br/><br/>Usage:<br/>    [p]fm artist [timeframe] toptracks <artist name><br/>    [p]fm artist [timeframe] topalbums <artist name><br/>    [p]fm artist [timeframe] overview  <artist name>

## fm profile
 - Usage: `[p]fm profile [user=None] `

Lastfm profile.

## fm recent
 - Usage: `[p]fm recent [size=15] `
 - Aliases: `recents and re`

Tracks you have recently listened to.

## fm compare
 - Usage: `[p]fm compare `

Compare two users music tastes

### fm compare artists
 - Usage: `[p]fm compare artists <user> [period=1month] `
 - Aliases: `artist`

Compare your top artists with someone else.<br/><br/>`[period]` can be one of: overall, 7day, 1month, 3month, 6month, 12month<br/>The default is 1 month.

### fm compare albums
 - Usage: `[p]fm compare albums <user> [period=1month] `
 - Aliases: `album`

Compare your top albums with someone else.<br/><br/>`[period]` can be one of: overall, 7day, 1month, 3month, 6month, 12month<br/>The default is 1 month.

### fm compare tracks
 - Usage: `[p]fm compare tracks <user> [period=1month] `
 - Aliases: `track`

Compare your top tracks with someone else.<br/><br/>`[period]` can be one of: overall, 7day, 1month, 3month, 6month, 12month<br/>The default is 1 month.

## fm topalbums
 - Usage: `[p]fm topalbums <args> `
 - Aliases: `talb`

Most listened albums.

## fm server
 - Usage: `[p]fm server `

LastFM Server Commands

### fm server topalbums
 - Usage: `[p]fm server topalbums `
 - Aliases: `talb`

Most listened albums in the server.

### fm server toptracks
 - Usage: `[p]fm server toptracks `
 - Aliases: `tt`

Most listened tracks in the server.

### fm server nowplaying
 - Usage: `[p]fm server nowplaying `
 - Aliases: `np`

What people on this server are listening to at the moment.

### fm server topartists
 - Usage: `[p]fm server topartists `
 - Aliases: `ta`

Most listened artists in the server.

### fm server chart
 - Usage: `[p]fm server chart <args> `

Visual chart of the servers albums, artists or tracks.

### fm server recent
 - Usage: `[p]fm server recent [size=15] `
 - Aliases: `recents and re`

Tracks recently listened to in this server.

## fm streak
 - Usage: `[p]fm streak [user=None] `

View how many times you've listened to something in a row<br/><br/>Only the most 200 recent plays are tracked

## fm scrobbler
 - Usage: `[p]fm scrobbler `

Toggles automatic scrobbling in VC.<br/><br/>Note: this also toggles the setting of now playing in VC as well.

## fm tag
 - Usage: `[p]fm tag `

Commands to tag things

### fm tag track
 - Usage: `[p]fm tag track `
 - Aliases: `tracks and song`

Commands to tag tracks

#### fm tag track list
 - Usage: `[p]fm tag track list [args] `

List tags for a track<br/><br/>If no arguments are given, the tags for the last track you listened to will be listed

#### fm tag track remove
 - Usage: `[p]fm tag track remove <args> `

Remove tags from a track<br/><br/>Tags are inputted as a comma separated list in the first group

#### fm tag track add
 - Usage: `[p]fm tag track add <args> `

Add tags to a track<br/><br/>Tags are inputted as a comma separated list in the first group

### fm tag album
 - Usage: `[p]fm tag album `
 - Aliases: `albums`

Commands to tag albums

#### fm tag album list
 - Usage: `[p]fm tag album list [args] `

List tags for an album<br/><br/>If no arguments are given, the tags for the last album you listened to will be listed

#### fm tag album remove
 - Usage: `[p]fm tag album remove <args> `

Remove tags from an album<br/><br/>Tags are inputted as a comma separated list in the first group

#### fm tag album add
 - Usage: `[p]fm tag album add <args> `

Add tags to an album<br/><br/>Tags are inputted as a comma separated list in the first group

### fm tag artist
 - Usage: `[p]fm tag artist `

Commands to tag tracks

#### fm tag artist list
 - Usage: `[p]fm tag artist list [artist] `

List tags for an artist<br/><br/>If no arguments are given, the tags for the last track you listened to will be listed

#### fm tag artist add
 - Usage: `[p]fm tag artist add <args> `

Add tags to an artist<br/><br/>Tags are inputted as a comma separated list in the first group

#### fm tag artist remove
 - Usage: `[p]fm tag artist remove <args> `

Remove tags from an artist<br/><br/>Tags are inputted as a comma separated list in the first group

## fm topartists
 - Usage: `[p]fm topartists <args> `
 - Aliases: `ta`

Most listened artists.

## fm love
 - Usage: `[p]fm love [track] `

Love a song on last.fm.<br/><br/>Usage:<br/>    [p]love<br/>    [p]love <track name> | <artist name>

## fm toptracks
 - Usage: `[p]fm toptracks <args> `
 - Aliases: `tt`

Most listened tracks.

## fm login
 - Usage: `[p]fm login `
 - Aliases: `set`
 - Checks: `tokencheck_plus_secret`

Authenticates your last.fm account.

## fm nowplaying
 - Usage: `[p]fm nowplaying [user=None] `
 - Aliases: `np`

Currently playing song or most recent song.

## fm lyrics
 - Usage: `[p]fm lyrics [track] `
 - Aliases: `lyr`

Currently playing song or most recent song.

## fm chart
 - Usage: `[p]fm chart <args> `

Visual chart of your top albums, tracks or artists.<br/><br/>Defaults to top albums, weekly, 3x3.

## fm wordcloud
 - Usage: `[p]fm wordcloud `
 - Aliases: `cloud and wc`
 - Checks: `wordcloud_available`

WordCloud Commands<br/><br/>Original idea: http://lastfm.dontdrinkandroot.net

### fm wordcloud tracks
 - Usage: `[p]fm wordcloud tracks [user=None] `
 - Aliases: `track`

Get a picture with the most listened to tracks.

### fm wordcloud albums
 - Usage: `[p]fm wordcloud albums [user=None] `
 - Aliases: `album`

Get a picture with the most listened to albums.

### fm wordcloud artists
 - Usage: `[p]fm wordcloud artists [user=None] `
 - Aliases: `artist`

Get a picture with the most listened to artists.

## fm unlove
 - Usage: `[p]fm unlove [track] `

Unlove a song on last.fm.<br/><br/>Usage:<br/>    [p]unlove<br/>    [p]unlove <track name> | <artist name>

## fm logout
 - Usage: `[p]fm logout `
 - Aliases: `unset`

Deauthenticates your last.fm account.

## fm last
 - Usage: `[p]fm last `

Your weekly listening overview.

# lastfmset
 - Usage: `[p]lastfmset `
 - Restricted to: `BOT_OWNER`
 - Aliases: `fmset`

Instructions on how to set the api key.

# crowns
 - Usage: `[p]crowns [user=None] `
 - Checks: `server_only and tokencheck`

Check yourself or another users crowns.

