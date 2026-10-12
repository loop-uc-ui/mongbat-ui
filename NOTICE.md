# What the MIT License does not cover

The [MIT License](LICENSE) covers the code in each release of mongbat-ui and
the documents in this repository. It does not cover the following. The paths
below are paths inside a release's zip file.

## Icons and textures

The pictures under `Icons/` and `Textures/` were generated with AI tools as
new versions of the icons in the Ultima Online Enhanced Client. Whether
anyone holds a copyright in them is not settled. This project claims no
copyright in them and grants no license to them.

## Fonts

`Fonts/Inter-Regular.ttf` and `Fonts/Inter-Medium.ttf` are the Inter typeface,
Copyright (c) 2016 The Inter Project Authors
(<https://github.com/rsms/inter>). The authors license it under the SIL Open
Font License 1.1. `Fonts/OFL.txt` holds that license.

## Material from the game client

Electronic Arts Inc. owns the material that these files take from the
client's default interface.

Two templates follow templates in it:

- `UI/Drag.xml`
- `UI/GenericGump.xml`

These files hold tables of game data that match the tables in it:

- `build/data/places.lua`: the named places on the map.
- `Icons/icons.xml`: the number and the name of each icon.
- `build/data/actionicons.lua` and `build/data/mapicons.lua`: the icons that
  an action or a map marker can be given.
- `build/data/stockCommands.lua`: the commands of the default interface's
  Actions window.
- `build/data/spellMenus.lua`: the spells that open a menu, and what each
  menu offers.
- `build/data/sextant.lua`: the arithmetic for a sextant reading.
- `lua/iconsizes.lua`: the size of each icon's picture.

No file from the game client is in a release. To use this UI you need your
own copy of the client.

## Trademark

Ultima Online is a trademark of Electronic Arts Inc. This project is not
affiliated with, or endorsed by, Electronic Arts Inc. or Broadsword Online
Games.
