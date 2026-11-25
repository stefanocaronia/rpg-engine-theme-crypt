# Crypt

A theme for the dashboard of [rpg-engine](https://github.com/stefanocaronia/rpg-engine), for any game system: vellum and iron-gall ink by day, bone on dark stone by candlelight. Titles in a blackletter, text in a humanist serif, a quatrefoil in the corner of the cards. Light and dark, both checked for contrast by the engine.

| | Light | Dark |
|---|---|---|
| Page | `#e9dfcb` vellum | `#0f0d0c` stone |
| Text | `#241a14` iron-gall | `#ece2cf` bone |
| Accent | `#5a2d6b` amethyst | `#c9a6dc` pale amethyst |
| Strong | `#c9a043` brass | `#d8a94a` candle |

## Its shapes

Cards with notched corners, flecks of vellum under their words and a rubric's double rule under their headers; square buttons and tabs, the tab chosen on a tint of amethyst; sharp sepia shadows, as of slabs laid on the page; portraits in a double ring of brass, like reliquary medallions; an arcade of pointed arches at the head of the page, beside the campaign's name; parchment for the documents and the maps. The double rule comes from its own style sheet, `style.css`, which Settings can turn off while the rest stays. Needs rpg-engine 0.22 or later.

## Install

- In the dashboard: **Packages › Add**, paste `https://github.com/stefanocaronia/rpg-engine-theme-crypt`, or find it in the catalog under Themes.
- Or from a terminal: `rpg package install https://github.com/stefanocaronia/rpg-engine-theme-crypt`.

Then choose it in **Settings › Dashboard › Theme**. It is installed for every campaign on this computer; `rpg package uninstall crypt` takes it away.

## Working on it

With rpg-engine 0.25 or later, the dashboard reads the theme from your own folder and shows each change as you save it.

1. Clone it wherever you like: `git clone https://github.com/stefanocaronia/rpg-engine-theme-crypt`.
2. Link it, from any folder: `rpg package install <the folder you cloned> --link`. It takes the place of the Crypt installed.
3. Open the dashboard of any campaign on this computer and choose Crypt in **Settings › Dashboard › Theme**.
4. Change `theme.yaml`, `style.css` and the pictures in `images/`: the page follows in a few seconds.

When a change fails a check, such as two colours that do not read on each other, the page goes back to its own look until it is fixed: `rpg package list`, or the dashboard's Packages page, says what is wrong and which colour would do. What each value changes is in rpg-engine's [game-systems.md](https://github.com/stefanocaronia/rpg-engine/blob/main/docs/game-systems.md#theme) and [dashboard-style.md](https://github.com/stefanocaronia/rpg-engine/blob/main/docs/dashboard-style.md#the-games-style).

`rpg package uninstall crypt` takes the link away, never your folder; install it again from GitHub to go back to the published one.

## Fonts

| Face | Used for | Licence |
|---|---|---|
| [Grenze Gotisch](https://github.com/Omnibus-Type/Grenze-Gotisch), Omnibus-Type | titles | SIL Open Font License 1.1, `fonts/grenze-gotisch/OFL.txt` |
| [Alegreya](https://github.com/huertatipografica/Alegreya), Huerta Tipográfica | text, story | SIL Open Font License 1.1, `fonts/alegreya/OFL.txt` |

Both come unchanged from [google/fonts](https://github.com/google/fonts).

## Licence

The theme, `theme.yaml`, `style.css` and `images/`, is © 2026 Stefano Caronia under [CC BY 4.0](LICENSE). The fonts stay under their own SIL Open Font License, beside each one.
