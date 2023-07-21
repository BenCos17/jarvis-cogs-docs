# Dev Help

Various development focused utilities.

# debug
 - Usage: `[p]debug <code> `
 - Restricted to: `BOT_OWNER`

Evaluate a statement of python code.<br/><br/>The bot will always respond with the return value of the code.<br/>If the return value of the code is a coroutine, it will be awaited,<br/>and the result of that will be the bot's response.<br/><br/>Note: Only one statement may be evaluated. Using certain restricted<br/>keywords, e.g. yield, will result in a syntax error. For multiple<br/>lines or asynchronous code, see [p]repl or [p]eval.<br/><br/>Environment Variables:<br/>    `ctx`      - the command invocation context<br/>    `bot`      - the bot object<br/>    `channel`  - the current channel object<br/>    `author`   - the command author's member object<br/>    `server`    - the current server object<br/>    `message`  - the command's message object<br/>    `_`        - the result of the last dev command<br/>    `aiohttp`  - the aiohttp library<br/>    `asyncio`  - the asyncio library<br/>    `discord`  - the discord.py library<br/>    `commands` - the redbot.core.commands module<br/>    `cf`       - the redbot.core.utils.chat_formatting module

# eval
 - Usage: `[p]eval <body> `
 - Restricted to: `BOT_OWNER`

Execute asynchronous code.<br/><br/>This command wraps code into the body of an async function and then<br/>calls and awaits it. The bot will respond with anything printed to<br/>stdout, as well as the return value of the function.<br/><br/>The code can be within a codeblock, inline code or neither, as long<br/>as they are not mixed and they are formatted correctly.<br/><br/>Environment Variables:<br/>    `ctx`      - the command invocation context<br/>    `bot`      - the bot object<br/>    `channel`  - the current channel object<br/>    `author`   - the command author's member object<br/>    `server`    - the current server object<br/>    `message`  - the command's message object<br/>    `_`        - the result of the last dev command<br/>    `aiohttp`  - the aiohttp library<br/>    `asyncio`  - the asyncio library<br/>    `discord`  - the discord.py library<br/>    `commands` - the redbot.core.commands module<br/>    `cf`       - the redbot.core.utils.chat_formatting module

# repl
 - Usage: `[p]repl `
 - Restricted to: `BOT_OWNER`

Open an interactive REPL.<br/><br/>The REPL will only recognise code as messages which start with a<br/>backtick. This includes codeblocks, and as such multiple lines can be<br/>evaluated.<br/><br/>Use `exit()` or `quit` to exit the REPL session, prefixed with<br/>a backtick so they may be interpreted.<br/><br/>Environment Variables:<br/>    `ctx`      - the command invocation context<br/>    `bot`      - the bot object<br/>    `channel`  - the current channel object<br/>    `author`   - the command author's member object<br/>    `server`    - the current server object<br/>    `message`  - the command's message object<br/>    `_`        - the result of the last dev command<br/>    `aiohttp`  - the aiohttp library<br/>    `asyncio`  - the asyncio library<br/>    `discord`  - the discord.py library<br/>    `commands` - the redbot.core.commands module<br/>    `cf`       - the redbot.core.utils.chat_formatting module

## repl pause
 - Usage: `[p]repl pause [toggle=None] `
 - Aliases: `resume`

Pauses/resumes the REPL running in the current channel.

# mock
 - Usage: `[p]mock <user> <command> `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Mock another user invoking a command.<br/><br/>The prefix must not be entered.

# mockmsg
 - Usage: `[p]mockmsg <user> [content] `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Dispatch a message event as if it were sent by a different user.<br/><br/>Current message is used as a base (including attachments, embeds, etc.),<br/>the content and author of the message are replaced with the given arguments.<br/><br/>Note: If `content` isn't passed, the message needs to contain embeds, attachments,<br/>or anything else that makes the message non-empty.

# bypasscooldowns
 - Usage: `[p]bypasscooldowns [toggle=None] `
 - Restricted to: `BOT_OWNER`

Give bot owners the ability to bypass cooldowns.<br/><br/>Does not persist through restarts.

