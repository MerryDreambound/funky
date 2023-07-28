# Keith

Keith is an open-source mods manager for Source Engine games, developed with Svelte, Electron and SkeletonUI. Currently still in early development, with support only for Left 4 Dead 2.

![App](/resources/app.png)

Initially inspired by Left 4 Dead 2's terrible in-game addons menu, I wanted something that gives me more functionallity, like search and a better method of solving conflicts, but the scope has since gotten much broader with lots of other great features and QoL improvements that are not possible in the in-game menu.

## ALPHA Roadmap

- [x] Richer display of mods with thumbnails
- [x] Search and filters
- [x] Broader mod categorization
- [x] More detailed mod inspection
- [x] Advanced mod conflict solving menu, showing you exactly which mods are conflicting
- [x] Support for different profiles, letting you quickly hop between various mod setups.
- [x] Mod shuffle/randomization. Change things up everytime you launch the game.
- [x] Pagination

## BETA Roadmap

- [ ] Extraction and inspection of VPK's contents
- [ ] Batch selection of mods w/ various actions
- [ ] (internal) userStore rewrite
- [ ] Built-in custom config/autoexec editor
- [ ] Local data backup
- [ ] General performance improvements and UI cleanup

## Ideas

- [ ] Collections
- [ ] Online data backup
- [ ] In-app unsubscribing from mods
- [ ] Custom vocalizer editor

## Project Setup

### Install

```bash
$ npm install
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
