# WeebBot-v2

Hey there. This is Weeb Bot. Currently it's core functionality is alerting for Emergency Quests on Phantasy Star Online 2. Pretty useful for end game grinding.

If you have any suggestions, or need any help, feel free to open an issue or join the bot's discord server: https://discord.gg/0xMXCNAFbH032Ig1

## How to install

Just clone this repo, edit the settings.py with your API Token and Owner ID, run the bot.py file, and you should be good to go. Requirements are discord.py, ffmpeg, requests and feedparser (for bumped article alerts).

## Commands

- `!help`: List of commands.
- `!cat`: Replies with a random cat gif and a random cat-related fact.
- `!pokemon name`: Retrives info about the pokemon named `name`.
- `!servers`: Prints every server your bot is in.
- `!eq enable`: Enables EQ Alerts on the channel the message is sent to.
- `!eq disable`: Disables EQ Alerts on the channel the message is sent to.
- `!lasteq`: Prints the last EQ sent by the bot.
- `!meme list`: Lists every meme in the ``audio`` folder.
- `!meme play name`: Joins sender's voice channel and plays ``name``.
 
## Owner only commands
- `!msg message`: Sends `message` to every server your bot is in.
- `!game name`: Changes game status to `name`.
