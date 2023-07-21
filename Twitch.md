# Twitch Help

Get twitch user information and post when a user gets new followers

# twitch
 - Usage: `[p]twitch `

Twitch related commands

## twitch user
 - Usage: `[p]twitch user [twitch_name=None] `
 - Aliases: `profile`

Shows basic Twitch profile information

## twitch set
 - Usage: `[p]twitch set <twitch_name> `

Sets the twitch user info for individual users to make commands easier

## twitch follows
 - Usage: `[p]twitch follows [twitch_name=None] `
 - Aliases: `followers`

Get latest Twitch followers

## twitch streams
 - Usage: `[p]twitch streams `

Twitch Stream commands

## twitch clips
 - Usage: `[p]twitch clips `

Twitch Clips commands

### twitch clips remclips
 - Usage: `[p]twitch clips remclips <twitch_name> [channel=None] `
 - Restricted to: `ADMIN`
 - Aliases: `removeclips, deleteclips and delclips`
 - Checks: `server_only`

Remove an account from new clip notifications in the specified channel<br/>defaults to the current channel

### twitch clips view
 - Usage: `[p]twitch clips view [twitch_name=None] `

Get latest twitch clips from a user

### twitch clips setclips
 - Usage: `[p]twitch clips setclips <twitch_name> [channel=None] [view_count=0] [check_back] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Setup a channel for automatic clip notifications<br/><br/>`<twitch_name>` The name of the streamers whose clips you want posted<br/>`[channel]` The channel to post clips into, if not provided will use the current channel.<br/>`[view_count]` The minimum view count required before posting a clip.<br/>`[check_back]` How far back to look back for new clips. Note: You must provide a number<br/>for `view_count` when providing the check_back. Default is 8 days.

## twitch setfollow
 - Usage: `[p]twitch setfollow <twitch_name> [channel=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Setup a channel for automatic follow notifications

## twitch remfollow
 - Usage: `[p]twitch remfollow <twitch_name> [channel=None] `
 - Restricted to: `ADMIN`
 - Aliases: `remove, delete and del`
 - Checks: `server_only`

Remove an account from follow notifications in the specified channel<br/>defaults to the current channel

## twitch creds
 - Usage: `[p]twitch creds `
 - Restricted to: `BOT_OWNER`

Set twitch client_id and client_secret if required for larger followings

## twitch testfollow
 - Usage: `[p]twitch testfollow <twitch_name> [channel=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Test channel for automatic follow notifications

