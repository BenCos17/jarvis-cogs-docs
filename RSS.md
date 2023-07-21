# RSS Help

RSS feeds for your server.

# rss
 - Usage: `[p]rss `
 - Restricted to: `MOD`
 - Checks: `server_only`

RSS feed stuff.

## rss add
 - Usage: `[p]rss add <feed_name> [channel=None] <url> `

Add an RSS feed to a channel.<br/><br/>Defaults to the current channel if no channel is specified.

## rss showtemplate
 - Usage: `[p]rss showtemplate <feed_name> [channel=None] `

Show the template in use for a specific feed.

## rss template
 - Usage: `[p]rss template <feed_name> [channel=None] [template] `

Set a template for the feed alert.<br/><br/>Each variable must start with $, valid variables can be found with `[p]rss listtags`.

## rss listall
 - Usage: `[p]rss listall `

List all saved feeds for this server.

## rss tag
 - Usage: `[p]rss tag `

RSS post tag qualification.

### rss tag allowlist
 - Usage: `[p]rss tag allowlist <feed_name> [channel=None] `

List allowed tags for feed post qualification.

### rss tag remove
 - Usage: `[p]rss tag remove <feed_name> [channel=None] [tag] `
 - Aliases: `delete`

Remove a tag from the allow list. The tag must match exactly (without regard to title casing).<br/>No regex or placeholder qualification.

### rss tag allow
 - Usage: `[p]rss tag allow <feed_name> [channel=None] [tag] `

Set an allowed tag for a feed to be posted. The tag must match exactly (without regard to title casing).<br/>No regex or placeholder qualification.<br/><br/>Tags can be found in `[p]rss listtags` under `$tags` or `$tags_list` (if tags are present in the feed - not all feeds have tags).

## rss embed
 - Usage: `[p]rss embed `

Embed feed settings.

### rss embed color
 - Usage: `[p]rss embed color <feed_name> [channel=None] [color] `
 - Aliases: `colour`

Set an embed color for a feed.<br/><br/>Use this command with no color to reset to the default.<br/>`color` must be a hex code like #990000, a [Discord color name](https://discordpy.readthedocs.io/en/latest/api.html#colour),<br/>or a [CSS3 color name](https://www.w3.org/TR/2018/REC-css-color-3-20180619/#svg-color).

### rss embed thumbnail
 - Usage: `[p]rss embed thumbnail <feed_name> [channel=None] [thumbnail_tag_name=None] `

Set a tag to be a thumbnail image.<br/><br/>This thumbnail will be applied to the first embed in the paginated list.<br/>Use this command with no thumbnail_tag_name to clear the embed thumbnail.

### rss embed toggle
 - Usage: `[p]rss embed toggle <feed_name> [channel=None] `

Toggle whether a feed is sent in an embed or not.<br/><br/>If the bot doesn't have permissions to post embeds,<br/>the feed will always be plain text, even if the embed<br/>toggle is set.

### rss embed image
 - Usage: `[p]rss embed image <feed_name> [channel=None] [image_tag_name=None] `

Set a tag to be a large embed image.<br/><br/>This image will be applied to the last embed in the paginated list.<br/>Use this command with no image_tag_name to clear the embed image.

## rss list
 - Usage: `[p]rss list [channel=None] `

List saved feeds for this channel or a specific channel.

## rss listtags
 - Usage: `[p]rss listtags <feed_name> [channel=None] `

List the tags available from a specific feed.

## rss force
 - Usage: `[p]rss force <feed_name> [channel=None] `

Forces a feed alert.

## rss limit
 - Usage: `[p]rss limit <feed_name> [channel=None] [character_limit=None] `

Set a character limit for feed posts. Use 0 for unlimited.<br/><br/>RSS posts are naturally split at around 2000 characters to fit within the Discord character limit per message.<br/>If you only want the first embed or first message in a post feed to show, use 2000 or less characters for this setting.<br/><br/>Note that this setting applies the character limit to the entire post, for all template values on the feed together.<br/>For example, if the template is `$title\n$content\n$link`, and title + content + link is longer than the limit, the link will not show.

## rss parse
 - Usage: `[p]rss parse `
 - Restricted to: `BOT_OWNER`

Change feed parsing for a specfic domain.<br/><br/>This is a global change per website.<br/>The default is to use the feed's updated_parsed tag, and adding a website to this list will change the check to published_parsed.<br/><br/>Some feeds may spam feed entries as they are updating the updated_parsed slot on their feed, but not updating feed content.<br/>In this case we can force specific sites to use the published_parsed slot instead by adding the website to this override list.

### rss parse remove
 - Usage: `[p]rss parse remove [website_url=None] `
 - Aliases: `delete and del`

Remove a website from the list for a time parsing override.<br/><br/>Use a website link formatted like `www.website.com` or `https://www.website.com`.<br/>For more information, use `[p]help rss parse`.

### rss parse add
 - Usage: `[p]rss parse add <website_url> `

Add a website to the list for a time parsing override.<br/><br/>Use a website link formatted like `www.website.com` or `https://www.website.com`.<br/>For more information, use `[p]help rss parse`.

### rss parse list
 - Usage: `[p]rss parse list `

Show the list for time parsing overrides.<br/><br/>For more information, use `[p]help rss parse`.

## rss remove
 - Usage: `[p]rss remove <feed_name> [channel=None] `
 - Aliases: `delete and del`

Removes a feed from a channel.<br/><br/>Defaults to the current channel if no channel is specified.

## rss find
 - Usage: `[p]rss find <website_url> `

Attempts to find RSS feeds from a URL/website.<br/><br/>The site must have identified their feed in the html of the page based on RSS feed type standards.

