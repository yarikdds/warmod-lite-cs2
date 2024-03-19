CS2 Match creation plugin
==============

CS2 plugin for creating and running matches directly from the server

## Installation
* Install Metamod (https://cs2.poggu.me/metamod/installation/)
* Install 
    * Releases page should contain a package that has everything, just move the contents to `cs2/game/csgo` folder
    * Verify the installation by typing `css_plugins list` and you should see p listed there.

## Features
- Easy creation of a match directly from the server
- Knife round (Can be toggled in setup phase)


## Commands

Commands can be triggered with either ! or .

### Setup phase

- `!map` Shows a selection menu for map in chat
- `!config` Print current config to chat
- `!start` Complete setup and transition to ready status state
- `!help` Print setup phase command usages
- `!knife <boolean>` Select if knife round should be played
- `!team_size <number>` Set team size (used when checking for ready status)

### ReadyUp phase

- `!r` or `!ready` Ready player
- `!ur` or `!unready` Unready player
- `!forceready` Force start match

For testing only
- `!bot_ct` Add bot for ct

### Knife phase

- `!switch` Switch sides
- `!stay` Stay on current side

For testing only
- `!kill` Kill self in game
- `!bot_ct` Add bot for ct

### Live phase

- `!pause` Pause match
- `!unpause` Unpause match

For testing only
- `!kill` Kill self in game
- `!bot_ct` Add bot for ct

## Configuration

All the Configuration files can be found in `csgo/cfg/MatchUp`


