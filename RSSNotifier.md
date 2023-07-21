# RSSNotifier Help

Get role and/or user mentions about feed updates.

# rssnotifier
 - Usage: `[p]rssnotifier `
 - Checks: `server_only`

RSSNotifier settings.

## rssnotifier adminoptout
 - Usage: `[p]rssnotifier adminoptout <feed_name> <channel> <user_ids> `

Force opt-out the users with given IDs from the given feed.<br/><br/>This can be useful, when the user is no longer in server, for example.<br/><br/>Use `[p]rss list` for the list of available feeds.

## rssnotifier removeroles
 - Usage: `[p]rssnotifier removeroles <feed_name> <channel> <roles> `
 - Aliases: `removerole`

Remove roles that should be mentioned when new message for given feed is sent.<br/><br/>Use `[p]rss list` for the list of available feeds.

## rssnotifier optout
 - Usage: `[p]rssnotifier optout <feed_name> [channel=None] `
 - Checks: `single_user_pings_enabled`

Opt-out of receiving notifications for the given feed name.<br/><br/>Use `[p]rss list` for the list of available feeds.

## rssnotifier addroles
 - Usage: `[p]rssnotifier addroles <feed_name> <channel> <roles> `
 - Aliases: `addrole`

Add roles that should be mentioned when new message for given feed is sent.<br/><br/>Use `[p]rss list` for the list of available feeds.

## rssnotifier listroles
 - Usage: `[p]rssnotifier listroles <feed_name> [channel=None] `

List role mentions list for the given feed name.<br/><br/>Use `[p]rss list` for the list of available feeds.

## rssnotifier optin
 - Usage: `[p]rssnotifier optin <feed_name> [channel=None] `
 - Checks: `single_user_pings_enabled`

Opt-in receiving notifications for the given feed name.<br/><br/>Use `[p]rss list` for the list of available feeds.

## rssnotifier usermentions
 - Usage: `[p]rssnotifier usermentions [state=None] `

Set whether users can opt-in receiving notifications.<br/><br/>**NOTE:** Generally, it is better to use role mentions<br/>and allow the users to self-assign the set role<br/>rather than have the bot send a lot of single user mentions.<br/><br/>This setting applies to whole server.<br/><br/>When this is enabled, users can use `[p]rssnotifier optin/optout`<br/>to opt-in/opt-out of receiving notifications for given rss feed.<br/><br/>When this is disabled, cog will ignore any users who have previously opted-in<br/>and only mention the roles set by server admins.<br/><br/>By default this is disabled<br/>and only the roles set by server admins will be mentioned.

