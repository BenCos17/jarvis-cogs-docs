# RemindMe Help

Never forget anything anymore.

# remindmeset
 - Usage: `[p]remindmeset `
 - Restricted to: `ADMIN`

Manage RemindMe settings.

## remindmeset metoo
 - Usage: `[p]remindmeset metoo `
 - Checks: `server_only`

Toggle the bot asking if others want to be reminded in this server.<br/><br/>If the bot doesn't have the Add Reactions permission in the channel, it won't ask regardless.

## remindmeset max
 - Usage: `[p]remindmeset max <maximum> `
 - Restricted to: `BOT_OWNER`

Global: Set the maximum number of reminders a user can create at one time.

## remindmeset settings
 - Usage: `[p]remindmeset settings `

Display current settings.

# reminder
 - Usage: `[p]reminder `

Manage your reminders.

## reminder list
 - Usage: `[p]reminder list [sort=time] `
 - Aliases: `get`

Show a list of all of your reminders.<br/><br/>Sort can either be:<br/>`time` (default) for soonest expiring reminder first,<br/>`added` for ordering by when the reminder was added,<br/>`id` for ordering by ID

## reminder remove
 - Usage: `[p]reminder remove <index> `
 - Aliases: `delete and del`

Delete a reminder.<br/><br/><index> can either be:<br/>- a number for a specific reminder to delete<br/>- `last` to delete the most recently created reminder<br/>- `all` to delete all reminders (same as [p]forgetme)

## reminder modify
 - Usage: `[p]reminder modify `
 - Aliases: `edit`

Modify an existing reminder.

### reminder modify time
 - Usage: `[p]reminder modify time <reminder_id> <time> `

Modify the time of an existing reminder.

### reminder modify repeat
 - Usage: `[p]reminder modify repeat <reminder_id> <time> `

Modify the repeating time of an existing reminder. Pass "0" to <time> in order to disable repeating.

### reminder modify text
 - Usage: `[p]reminder modify text <reminder_id> <text> `

Modify the text of an existing reminder.

## reminder create
 - Usage: `[p]reminder create [time_and_optional_text] `
 - Aliases: `add`

Create a reminder with optional reminder text.<br/><br/>Same as `[p]remindme`, so check that for usage help.

# remindme
 - Usage: `[p]remindme [time_and_optional_text] `

Create a reminder with optional reminder text.<br/><br/>Either of the following formats are allowed:<br/>`[p]remindme [in] <time> [to] [reminder_text]`<br/>`[p]remindme [to] [reminder_text] [in] <time>`<br/><br/>`<time>` supports commas, spaces, and "and":<br/>`12h30m`, `6 hours 15 minutes`, `2 weeks, 4 days, and 10 seconds`<br/>Accepts seconds, minutes, hours, days, and weeks.<br/><br/>You can also add `every <repeat_time>` to the command for repeating reminders.<br/>`<repeat_time>` accepts days and weeks only, but otherwise is the same as `<time>`.<br/><br/>Examples<br/>--------<br/>`[p]remindme in 8min45sec to do that thing`<br/>`[p]remindme to water my plants in 2 hours`<br/>`[p]remindme in 3 days`<br/>`[p]remindme 8h`<br/>`[p]remindme every 1 week to take out the trash`<br/>`[p]remindme in 1 hour to drink some water every 1 day`

# forgetme
 - Usage: `[p]forgetme `

Remove all of your upcoming reminders.

