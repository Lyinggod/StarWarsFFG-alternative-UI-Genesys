All stated changes are pending. This fork has been heavily modified to support the Genesys RPG when played in the FFG Star Wars system setting. A list of modifications can be found at the bottom of the description.

# Star Wars FFG Alternative UI

This module change the dispatch of datas into some sheets.
Sheets reworked are the following:

* Actors: Character, minion, rival, nemesis, vehicle
* Journal
* some items:
  * Weapons
  * Armors
  * Gears
  * Talents
  * Species
  * Careers
  * Ship weapons
  * item Attachments
  * Item modifiers
  * Ship attachments
  * Critical hits
  * Critical injuries
  * Specializations
  * Force powers
  * Signature abilities

## Themes

The module have 3 themes. You can change it the module settings:

* Light: Keep the color of the default theme from the system
* Main: All alternative sheets use the same palette of colors
* Datapad: All alternative sheets use the same palette of colors and use a datapad image

## Setting colors

In the module option you can change some colors for the Main and Datapad theme:

* Main text
* Actor and Item name
* Header text color (Block title, List title, Characteristics title)
* Header background color (Block title, List title, Characteristics title)
* Blocks background color (Wounds, Soak, Menu icon, ...)
* Current hardpoint text color
* Negative current hardpoint background color
* Positive current hardpoint background color
* Link text color (Actor, Item links in description or Journal. And for the vehicle crew)
* Focused field background color
* Focused field text color

# Installation

## Method

1. On Foundry VTT's __Configuration and Setup__ screen, go to __Add-on Modules__
2. Click __Install Module__
3. In the Manifest URL field, paste: `https://raw.githubusercontent.com/TeddyBears/StarWarsFFG-alternative-UI/main/module.json`
4. Click __Install__ next to the pasted Manifest URL

# Setup

In the sheet options you can change the field `this sheet` to the alternative version.
Or in the main settings you can set the alternative version in `Core - Configue default sheets`.

# Recommended Modules

This module uses the [Color Picker](https://foundryvtt.com/packages/color-picker) library module for its color picker settings.

# Changelog

Changelog are available [here](https://github.com/TeddyBears/StarWarsFFG-alternative-UI/blob/main/CHANGELOG.md)

# Wiki

See the [wiki](https://github.com/TeddyBears/StarWarsFFG-alternative-UI/wiki/Home) for screenshots and more details about the new dispatch into sheets

# Genesys Modifications
Subcategories have been added to the following items and displayed as separate lists on the actor. List modifications are done via Configure Settings:

<img src="https://github.com/user-attachments/assets/73e820ce-c26b-41a3-9fba-46e5228ce0d3" width=400>

Categories are displayed in their respective areas on the actor sheet.

The specialization item template now functions in the same way as the talent template but without the tier or rank fields.

