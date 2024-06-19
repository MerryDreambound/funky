# Funky

Funky is an open-source mods manager for Left 4 Dead 2, developed with Electron, Dexie, Svelte and SkeletonUI.

![App](/resources/app.png)

Initially inspired by Left 4 Dead 2's terrible in-game addons menu, I wanted something that gives me more functionality, like search and a better method of solving conflicts, but the scope has since gotten much broader with lots of other great features and QoL improvements that are not possible in the in-game menu.

## Features

- [x] Grid display with thumbnails and pagination
- [x] Search and filters
- [x] Automatic mod categorization based on mod contents
- [x] Much more detailed mod overview with useful actions
- [x] Conflict solving menu, showing you exactly which mods are conflicting
- [x] Profiles, letting you quickly hop between different setups
- [x] Shuffles, randomizing your mod selection every time you boot up the game
- [x] Batch selection of mods with various actions
- [x] Unsubscribing from mods via Steam Web API
- [x] VPK browser with extraction functionality

## Ideas

Here are some ideas or features I'd still like implemented one day

- [ ] List view of mods
- [ ] Built-in custom config/autoexec editor
- [ ] Local data backup
- [ ] Online data backup
- [ ] Collections
- [ ] Vocalizer editor

## Caveats

While I've found Funky to be extremly useful in organizing my ever growing library of mods, there's some things to keep in mind:

- The game needs to be restarted before any changes made in Funky can take effect.
- Newly subscribed-to Workshop mods will only be downloaded after you start the game.

So taking both of these points into account, if you've just subscribed to a new mod, you'll have to open up the game, wait for the game to download the mod, close the game, make any changes in Funky and then finally, run the game from within Funky in order for all changes to take effect. Quite clumbersome, but it is what it is.

## Project Setup

### Prep submodules

```bash
$ git submodule init
$ git submodule update
```

### Install dependencies

```bash
$ npm i
```

### Development

```bash
$ npm run dev
```

### Build

```bash
# For windows
$ npm run build:win

# For macOS
$ npm run build:mac

# For Linux
$ npm run build:linux
```
