# Changelog

## v0.16.5

- Updates requirements.txt to work with lastest discord.py
- Update rolem to support renaming role
- Added alias role_m to rolem
- Added example to show how to change auth_plugin

## v0.16.4

### Frontend

- Made ?roles order by name, instead of by the arbitrary ID

### Backend

- Cleaned up about_pings
- Moved from `click` to `tqdm` for progress bars

## v0.16.3

- Cleanup of the Git repo to remove bits of the data directory which won't be needed for other hosts

## v0.16.2

- Fixed handling when `?role leave` is used on a role which does not exist
- Added command `?role info [role_name]` to get info about a role

## v0.16.1

- Patch to work with latest discord.py

## v0.16.0

- Make skip scrape also skip the scraping done in bot.py
- Add tool on [prefix]sync to auto copy the current sever structure, permissions and roles, to another test environment

## v0.15.1

- Show already guessed letters in hangman
- Remove responding to invalid guesses in hangman (unless entire word)
- Make version update when the text file is updated
- Add indicator to show when files are likely newer than version running

## v0.15.0

- Added hangman, as proof of concept game!

## v0.14.1

- Fixed issue when channels had emoji in their names and a DB was set up badly

## v0.14.0

- Move admin and ping commands into groups of subcategories, to clean up commands (run `help` to see new subcategories)
- Added hidden redirects for old user facing commands to ease into transition
- Added sharding support when running at scale
- Added command to get average latency of bot, and specific information about best and worst shards currently

## v0.13.2

- Made flag output prettier, with actual mentions and links

## v0.13.1

- Added "github" command to get github link

## v0.13

- Renamed "slurs" cog to "flags"
- Changed flags to work per server, instead of being global
- Fixed minor bugs
## v0.12

- Made roles per server instead of global on the bot
- Add `my_roles` command to list roles you are a part of currently
- Set roles to is_joinable when being imported if they are currently mentionable
- Cleanup of root directory

## v0.11

Start of changelog