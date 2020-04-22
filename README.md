# NHLBot

1. Use `?subscribe [team]` to create game day channels for your team(s). 
   - `[team]` is the 3 letter code for the team (same as the ones that are displayed on the tv scores)
   - Use `?subscribe help` to get the list of codes.

# Features
## Game Day Channels
- [x] Automatically generate channels for individual games
- [x] Give warnings before the game starts (60/30/10 minutes before).
- [x] Display messages for when goals are scored.
- [x] Display summaries of games.
- [x] Special messages for when canucks score.

## Commands
`?nhlbot [command]`
- `fuckmessier` Fuck Messier.
- `subscribe [team]` Subscribes you or your guild to the team specified by `[team]`. `[team]` is the 3 letter code representing the team you want to subscribe to. This must be done by an user with admin priveledges on the server/guild. 
- `unsubscribe [team]` Unsubscribes you or your guild from a team.
- `schedule` Replies with information about recent and upcoming games.
- `about` Displays information about bot/author.
- `help` Display list of commands.

### In 'Game Day Channels' only
- `score` Displays score of that game.
- `goals` Displays goals of that game.

# Other

## Permissions for NHLBot

- Manage Channels
- Read Messages
- Embed Links
- Read Message History
- Send Messages
- Manage Messages
- Attach Files
- Add Reactions
