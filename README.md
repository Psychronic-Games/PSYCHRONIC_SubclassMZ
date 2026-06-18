# PSYCHRONIC_SubclassMZ

**RPG Maker MZ Plugin**

Adds possibility of Sub-Class for Actors with full trait support

## What It Does

This plugin allows actors to have a subclass in addition to their main class.

## Plugin File

- `PSYCHRONIC_SubclassMZ.js`
- Target: RPG Maker MZ
- Author: Psychronic
- URL: https://psychronic.itch.io

## Plugin Commands

- `refreshSubclass`

## Installation

1. Download `PSYCHRONIC_SubclassMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Full Plugin Help

This plugin allows actors to have a subclass in addition to their main class.

### How to Use

In the Notes field of an Actor, add:
<Subclass: X>

Where X is the ID of the class you want as the subclass.

Example: <Subclass: 54>

IMPORTANT: After adding a subclass tag to an actor, you must either:
- Start a new game, OR
- Remove and re-add the actor to your party

### Features

- Actor stats are averaged between main class and subclass
- Actor learns skills from both main class and subclass
- Actor can use skill types from both classes
- Actor can equip weapons/armor from both classes
- Element rates, state rates, and debuff rates are averaged
- Ex-parameters and Sp-parameters are averaged
- Attack elements and states are combined from both classes
- Special flags and party abilities are combined from both classes
- Subclass is displayed in menus alongside main class

### Plugin Commands

Refresh Subclass - Forces an actor to refresh their subclass data
actorId: The ID of the actor to refresh

### Terms of Use

Free for commercial and non-commercial use.
Credit Psychronic if you use this plugin.

@command refreshSubclass
@text Refresh Subclass
@desc Forces an actor to refresh their subclass data

@arg actorId
@text Actor ID
@desc The ID of the actor to refresh
@type actor
@default 1

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
