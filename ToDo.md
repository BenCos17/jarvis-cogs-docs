# ToDo Help

A todo list for keeping track of tasks you have to do<br/><br/>This cog is my oldest, still standing cog and holds a special place in my heart even though it's a pain to work on lol<br/><br/>I hope you have as much fun with it as I had designing it ❤<br/>- Jojo#7791

# todoset
 - Usage: `[p]todoset `
 - Aliases: `todosettings`

Commands for configuring your todo list

## todoset showsettings
 - Usage: `[p]todoset showsettings `

Show your todo settings<br/><br/>This will list the following:<br/>    - `indexed todos`<br/>    - `colour`<br/>    - `emojis`<br/>    - `embedded`<br/>    - `markdown`<br/>    - `autosort`<br/>    - `combined lists`<br/>    - `pretty todos`<br/>    - `timestamps`<br/>    - `extra details`

## todoset completeemoji
 - Usage: `[p]todoset completeemoji <reset> [emoji=None] `
 - Aliases: `cemoji`
 - Checks: `pretty`

Set the completed emoji used for completed todos.<br/><br/>This will prompt you to react with an emoji.<br/>Note that only emojis that [botname] can use will work<br/><br/>**Arguments**<br/>    - `reset` Whether to reset the emoji back to default.<br/>    - `emoji` The emoji to use for the complete mark. This has to be custom and can only be an emoji that [botname] can use.

## todoset combine
 - Usage: `[p]todoset combine <value> `
 - Aliases: `combined`

Combine your todo list with your completed list<br/><br/>**NOTE** this will only be in effect if you have completed todos<br/><br/>**Arguments**<br/>    - `value` Whether to combine your lists or not

## todoset preset
 - Usage: `[p]todoset preset <preset> `

Set you settings to a preset<br/><br/>Current presets are `minimal` and `pretty`<br/><br/>**Arguments**<br/>    - `preset` The preset for your settings. Must be either `minimal` or `pretty` as of right now.

## todoset markdown
 - Usage: `[p]todoset markdown <value> `
 - Aliases: `md and codeblock`

Set your todo list to use markdown blocks<br/><br/>This will look something like this<br/>**Jojo's todos**<br/>```md<br/>1. Blah blah<br/>2. Blah blah blah<br/>3. aaaaaaaaaaaaaaaaaaa<br/>```<br/>**Arguments**<br/>    - `value` Whether markdown should be used or not

## todoset colour
 - Usage: `[p]todoset colour <colour> `

Set the colour of your todo list's embeds<br/><br/>**NOTE** this will only work if you have embeds enabled and the bot can embed links in the channel<br/><br/>**Arguments**<br/>    - `colour` The colour you would like the embed to be. Type `None` to set it to the bot's default embed colour

## todoset timestamps
 - Usage: `[p]todoset timestamps <value> `
 - Aliases: `timestamp and ts`

Set whether todo should use timestamps<br/><br/>**NOTE** this will only be in effect if the message is not embedded. This might also be removed at a later date<br/><br/>**Arguments**<br/>    - `value` Whether to enable timestamps

## todoset pretty
 - Usage: `[p]todoset pretty <value> `

Have your todo list look pretty<br/><br/>This will set it to use emojis such as ✅ and 🟩<br/><br/>**Arguments**<br/>    - `value` Whether pretty should be enabled

## todoset private
 - Usage: `[p]todoset private <value> `

Set your todo list to display privately<br/><br/>This will make the menu be ephemeral when you use it<br/><br/>**Arguments**<br/>    - `value` Whether your todo list should be private.

## todoset categoryemojis
 - Usage: `[p]todoset categoryemojis `
 - Aliases: `catemojis`

Set your category emojis

### todoset categoryemojis completedemoji
 - Usage: `[p]todoset categoryemojis completedemoji <reset> [emoji=None] `
 - Aliases: `cemoji`

Set the emoji for the completed category.<br/><br/>If you have markdown enabled only default emojis will work.<br/><br/>By default the emoji will be '☑'.<br/><br/>**Arguments**<br/>    - `reset` If specified this will reset the emoji back to default.<br/>    - `emoji` The emoji that will be used for the category. This will skip the check, and this argument can't be used if you have markdown enabled.

### todoset categoryemojis todoemoji
 - Usage: `[p]todoset categoryemojis todoemoji <reset> [emoji=None] `
 - Aliases: `temoji`

Set the emoji for the todo category.<br/><br/>If you have markdown enabled only default emojis will work.<br/><br/>By default the emoji will be '🔘'.<br/><br/>**Arguments**<br/>    - `reset` If specified this will reset the emoji back to default.<br/>    - `emoji` The emoji that will be used for the category. This will skip the check. This argument can't be used if you have markdown enabled.

## todoset embeds
 - Usage: `[p]todoset embeds <value> `
 - Aliases: `embed`

Set your todo list to use embeds<br/><br/>**NOTE** embeds will *only* be used if possible in the current channel<br/><br/>**Arguments**<br/>    - `value` Whether to use embeds or not

## todoset details
 - Usage: `[p]todoset details <value> `

Have your todo list send you extra details.<br/><br/>This may be removed at a later date<br/><br/>**Arguments**<br/>    - `value` Whether you should recieve extra details

## todoset number
 - Usage: `[p]todoset number <value> `
 - Aliases: `index`

Set your todo list to index todos whilst listing them<br/><br/>**Arguments**<br/>    - `value` Whether to index todos or not

## todoset todoemoji
 - Usage: `[p]todoset todoemoji <reset> [emoji=None] `
 - Aliases: `temoji`
 - Checks: `pretty`

Set the emoji used for todos<br/><br/>This will prompt you to react with an emoji. Note that the emoji must be one the bot can use.<br/><br/>If you have markdown enabled only default emojis will work.<br/><br/>**Arguments**<br/>    - `reset` Whether to reset the emoji back to default.<br/>    - `emoji` The emoji that will be used for this

## todoset autosort
 - Usage: `[p]todoset autosort <value> `

Set your todo list to auto sort<br/><br/>**NOTE** This command won't autosort your todos. Use `[p]todo sort` to sort your todos<br/><br/>**Arguments**<br/>    - `value` Whether your todo list should auto sort

# todo
 - Usage: `[p]todo <index> `

Your todo list inside Discord<br/><br/>**Arguments**<br/>    - `index` The todo you want to view.<br/>    This is optional and if left out, it will show the help command instead

## todo add
 - Usage: `[p]todo add <pinned> <todo> `

Add a todo task to your list<br/><br/>Don't store sensitive information here for Pete's sake<br/><br/>**Arguments**<br/>    - `pinned` A boolean value that sets it to be pinned or not. Defaults to False<br/>    - `todo` The todo task

## todo search
 - Usage: `[p]todo search <regex> <query> `

Query your todo list for todos containing certain words<br/><br/>**Arguments**<br/>    - `query` The words to search for.

## todo suggestors
 - Usage: `[p]todo suggestors `

A thank you command for everyone who has either contributed, requested a feature, or reported a bug

## todo manager
 - Usage: `[p]todo manager `
 - Aliases: `managers`

Manage who can manage your todo lists. These people can add and remove from your todo list, so be careful who you grant this to

### todo manager add
 - Usage: `[p]todo manager add <user> `

Add a user to your todo list managers<br/><br/>This user cannot be a bot. Please be aware that they can add and remove from your todo list and they can view it at any time<br/><br/>**Arguments**<br/>    - `user` The user you would like to add to your list's managers.

### todo manager list
 - Usage: `[p]todo manager list `

List your todo list's managers

### todo manager remove
 - Usage: `[p]todo manager remove <user> `
 - Aliases: `del and delete`

Remove a user from your list's managers<br/><br/>This user cannot be a bot<br/><br/>**Arguments**<br/>    - `user` The user to remove from your managers

## todo delete
 - Usage: `[p]todo delete <indexes> `
 - Aliases: `del, remove, clear and r`

Delete a todo task<br/><br/>This will remove it from your list entirely<br/><br/>**Arguments**<br/>    - `indexes` The indexes of the todos you want to delete

## todo shared
 - Usage: `[p]todo shared `
 - Checks: `server_only`

Shared todo lists.<br/><br/>These are lists that other users have given you access to, for adding/removing/completing

### todo shared pin
 - Usage: `[p]todo shared pin <user> <index> `
 - Aliases: `unpin`

Pin a user's todo<br/><br/>This will only work if you manage that user's list<br/><br/>**Arguments**<br/>    - `user` The user to pin a todo for. This **cannot** be a bot.<br/>    - `index` The index of the todo to pin.

### todo shared list
 - Usage: `[p]todo shared list <user> `

Lists a user's list that you manage<br/><br/>This will *only* work if you manage that user's list<br/><br/>**Arguments**<br/>    - `user` A user who you manage a list for. This **cannot** be a bot.

### todo shared view
 - Usage: `[p]todo shared view <user> <index> `

View a todo of a user who's list you manage<br/><br/>This only works if you manage that user's list<br/><br/>**Arguments**<br/>    - `user` The user of which you're viewing the todo.<br/>    - `index` The index of the todo you want to view.

### todo shared complete
 - Usage: `[p]todo shared complete <user> <indexes> `
 - Aliases: `c`

Complete todos on a user's list<br/><br/>This only works if you are a moderator of that user's list<br/><br/>**Arguments**<br/>    - `user` The user for completing todos. This **cannot** be a bot.<br/>    - `indexes` The indexes of the todos you want to complete

#### todo shared complete list
 - Usage: `[p]todo shared complete list <user> `

List a user's completed todos<br/><br/>This only works if you are a manager of that user's todo list<br/><br/>**Arguments**<br/>    - `user` The user to view the list of. This **cannot** be a bot.

### todo shared remove
 - Usage: `[p]todo shared remove <user> <indexes> `
 - Aliases: `del and delete`

Remove a todo from a user's list<br/><br/>This will only work if you are a manager of that user's list<br/><br/>**Arguments**<br/>    - `user` The user you want to edit the list of. This **cannot** be a bot.<br/>    - `index` The index of the todo you want to remove.

### todo shared add
 - Usage: `[p]todo shared add <user> <pinned> <todo> `

Add a todo to a user's list<br/><br/>This will require you to have manager on their list<br/><br/>**Arguments**.<br/>    - `user` The user to add to their list. This **cannot** be a bot.<br/>    - `pinned` Whether the todo should be pinned or not. Defaults to False.<br/>    - `todo` The task to add to the user's list.

## todo complete
 - Usage: `[p]todo complete <indexes> `
 - Aliases: `c`

Commands having to do with your completed tasks<br/><br/>**Arguments**<br/>    - `indexes` Optional indexes to complete. If left at none the help command will be shown

### todo complete delete
 - Usage: `[p]todo complete delete <indexes> `
 - Aliases: `del, remove and clear`

Delete completed todos<br/><br/>This will remove them from your completed list<br/><br/>**Arguments**<br/>    - `indexes` A list of integers for the indexes of your completed todos

### todo complete reorder
 - Usage: `[p]todo complete reorder <original> <new> `
 - Aliases: `move`

Move a completed todo from one index to another<br/><br/>This will error if the index is larger than your completed todo list<br/><br/>**Arguments**<br/>    - `from` The index of the completed todo<br/>    - `to` The new index of the completed todo

### todo complete deleteall
 - Usage: `[p]todo complete deleteall [confirm=False] `
 - Aliases: `delall, removeall and clearall`

Remove all of your completed todos<br/><br/>**Arguments**<br/>    - `confirm` Skips the confirmation check. Defaults to False

### todo complete view
 - Usage: `[p]todo complete view <index> `

View a completed todo. This has a similar effect to using `[p]todo <index>`<br/><br/>This will have a menu that will allow you to delete the todo<br/><br/>**Arguments**<br/>    - `index` The index of the todo you want to view.

### todo complete list
 - Usage: `[p]todo complete list `

List your completed todos<br/><br/>This will only list if you have completed todos

## todo reorder
 - Usage: `[p]todo reorder <original> <new> `
 - Aliases: `move`

Move a todo from one index to another<br/><br/>This will error if the index is larger than your todo list<br/><br/>**Arguments**<br/>    - `from` The index of the todo<br/>    - `to` The new index of the todo

## todo pin
 - Usage: `[p]todo pin <index> `
 - Aliases: `unpin`

Pin or unpin a todo<br/><br/>This will stick it at the top of the list whenever you view it<br/><br/>**Arguments**<br/>    - `index` The index of the todo you want to pin/unpin

## todo edit
 - Usage: `[p]todo edit <index> <new_todo> `

Edit a todo!

## todo suggestions
 - Usage: `[p]todo suggestions `
 - Aliases: `suggest`

Get information about how you can suggest features for this cog

## todo multiadd
 - Usage: `[p]todo multiadd [todos] `

Add multiple todos in one command. These are split by a newline.<br/><br/>You can upload a file instead of inputting the todos, or reply to a message that contains a file<br/>**Examples**<br/>`[p]todo multiadd Todo number 1<br/>todo number 2<br/>todo number 3`<br/><br/>**Arguments**<br/>    - `todos` The todos you want to add.<br/>    This is an optional argument and you can upload, or reply to a message with, a file instead

## todo list
 - Usage: `[p]todo list `

List your todos<br/><br/>This will list them with pinned todos first and then whatever sorting you have

## todo deleteall
 - Usage: `[p]todo deleteall [confirm=False] `
 - Aliases: `delall, removeall and clearall`

Remove all of your todos<br/><br/>**Arguments**<br/>    - `confirm` Skips the confirmation check. Defaults to False

## todo sort
 - Usage: `[p]todo sort [reverse=None] `

Sort your todos by alphabetical order<br/><br/>You can optionally set it to sort in reverse<br/><br/>**Arguments**<br/>    - `reverse` Whether to set it to be reversed. Defaults to False

## todo import
 - Usage: `[p]todo import [confirm=False] `

Import your todos from epic guy's todo cog.<br/><br/>This will only import todos from this bot's config.<br/>To import todos from another bot, check out `[p]todo multiadd`<br/><br/>**Arguments**<br/>    - `confirm` Skips the confirmation check.

## todo gettodos
 - Usage: `[p]todo gettodos `
 - Aliases: `todotofile`
 - Checks: `attach_or_in_dm`

Grab your todos in a clean file format.<br/><br/>This is handy for moving todos over from bot to bot

## todo importall
 - Usage: `[p]todo importall [confirm=False] `
 - Restricted to: `BOT_OWNER`

Import every user's todos from epic guy's todo cog<br/><br/>This will only import todos from this bot's config.<br/><br/>**Arguments**<br/>    - `confirm` Skips the confirmation check.

