---
title: "Yohane Commands"
old_id: 4
---
These are the commands for the Yohane bot.

## Yohane In-Game

### General commands
- `!roll [number]` - Rolls a random number
- `!help` - Shows a list of all commands
- `!subscribe pp [options]` - Notifies about the pp status such as limit after [submitting a score](https://cdn.discordapp.com/attachments/265909019976138754/801454622346444860/unknown.png). (options: `set`, `get`, `unset`, `toggle`)
- `!boardshow [options]` - [Experimental] Hide yourself from the leaderboard (options: `others`, `normal`)
- `!report` - If you encounter any player breaking the rules, use this command to notify our staff.
- `!faq list` - Returns a list of things that are often needed in chat.

### Multiplayer commands

- `!mp help` - Shows a list of all multiplayer commands.
- `!mp make [name]` - Creates a multiplayer room.
- `!mp close` - Closes the current multiplayer room.
- `!mp checkperm` - Displays your permission level for the current room.
- `!mp listref` - Displays a list of referees in the room.
- `!mp addref <username>` - Adds user as a referee in the room.
- `!mp rmref <username>` - Removes user as referee in the room.
- `!mp start [timer]` - Automatically sets all players to "ready" and starts the game after a timeout (Default: `0`). Can be used to play solo in a multiplayer room.
- `!mp abort` - Aborts the game. *This is different from using the `Escape`-key in solo*

Note: For every operation that uses the Username Lookup, you can use `#<UserID>` instead.

### Admin commands
- `!system restart` - Restart the server. Everyone will be disconnected and reconnected automatically
- `!system status` - Show server status
- `!system reload` - Reload bancho settings (the one that are editable from DAP)
- `!system maintenance on/off` - Turn on/off bancho maintenance mode
- `!moderated on/off` - Turn on/off moderated mode for the current channel
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silence a user
- `!removesilence <target>` - Remove target's silence
- `!kick <username>` - Kick an user from the server
- `!ban <username>` - Ban and kick someone
- `!unban <username>` - Unban someone
- `!restrict <username>` - Restrict someone
- `!unrestrict <username>` - Unrestrict someone  
- `!bot reconnect` - Reconnect YohaneBOT in case she's not listed online anymore
- `!alert <message>` - Send a notification to every user connected to bancho
- `!alertuser  <username> <message>` - Send a notification to a specific user
- `!whitelist <username> <mode> <type> [procedure]` - Adds user to the PP limit whitelist.
    
    | Parameter | Value | Function |
    | :-- | :-: | :-- |
    | `mode` | `vanilla`, `relax` | Specifies the game mode for the *whitelist* |
    | `type` | `total`, `all` | Specifies the type of limit for the *whitelist* |
    | `procedure` | `add`, `set` | *Optional*<br>Specifies the operation of changing the PP value for the *whitelist* |
- `!map <command> <type> <ID>` - Performs operations on a map(set)
    
    | Parameter | Value | Function |
    | :-- | :-: | :-- |
    | `command` | `rank`, `love`, `unrank`, `reset` | Directly changes the status of the map. |
    | `command`\* | `auto-rank`, `auto-love`, `auto-cancel` | **Can only be set by someone permitted to manage autoranks**<br>Sets the eligibility of a map to get auto-rank. |
    | `type` | `set`, `set-of`, `map` | `set` - uses **mapset ID** to retrieve data.<br>`set-of` - uses **map ID** to get **a list of maps with the mapset ID** from the given **map ID**.<br>`map` - uses **map ID** to retrive data. |
    
    For more details, you may take a look at [this example](https://cdn.discordapp.com/attachments/265909019976138754/801471868699410473/unknown.png).

### Note
If you're using commands through Yohane's private message, you don't need to use the "!"-prefix.
- Outside of that, you need to use the "!"-prefix to invoke Yohane's commands.

## YohaneBot Discord
- `@faq help` - Shows all commands
- `@stats [options] [mode]` - Displays profile status (options: `vanilla`, `relax`) (mode: `std`, `taiko`, `mania`, `ctb`)
- `@recent [options] [nickname]` - Displays the most recent score (options: `vanilla`, `relax`)
- `@top [options] [nickname]` - Displays the top score (options: `vanilla`, `relax`)
