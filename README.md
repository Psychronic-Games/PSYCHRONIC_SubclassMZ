# PSYCHRONIC_SubclassMZ

Adds possibility of Sub-Class for Actors with full trait support

## What It Does

This plugin allows actors to have a subclass in addition to their main class.

## Highlights

- Actor stats are averaged between main class and subclass
- Actor learns skills from both main class and subclass
- Actor can use skill types from both classes
- Actor can equip weapons/armor from both classes
- Element rates, state rates, and debuff rates are averaged
- Ex-parameters and Sp-parameters are averaged
- Attack elements and states are combined from both classes
- Special flags and party abilities are combined from both classes
- Subclass is displayed in menus alongside main class

## Plugin Commands

- refreshSubclass

## Basic Usage

In the Notes field of an Actor, add:
<Subclass: X>
Where X is the ID of the class you want as the subclass.
Example: <Subclass: 54>
IMPORTANT: After adding a subclass tag to an actor, you must either:
- Start a new game, OR
- Remove and re-add the actor to your party

## Compatibility

- RPG Maker MZ
- JavaScript plugin for `js/plugins/`

## Installation

1. Download `PSYCHRONIC_SubclassMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.

## Source

This version was exported from the RPG Reactor Complex template source plugin folder.

## Author

Psychronic

https://psychronic.itch.io

## License

MIT. See `LICENSE`.
