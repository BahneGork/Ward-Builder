# Ward Builder

An abstract city map builder for tabletop RPG cities: wards and the borders between them, grouped into districts,
controlled by factions, with power centres, points of interest, alliances and rivalries.

Open it at **https://bahnegork.github.io/Ward-Builder/** (or open `index.html` straight from disk). It is one
self-contained HTML file with no external dependencies.

## Saving your work

The tool autosaves **only in your own browser**, separately for each address you open it from. Browser storage
can be cleared or lost, so export regularly:

- **File → Export map JSON** saves the whole city as a JSON file.
- **File → Import map JSON** loads one back (this replaces the city currently open).

## Cities

City data is kept in `cities/<city>/<version>.json`, one file per version of a city. Each campaign that uses a
city has its own version, e.g. `cities/arendur/arendur-rising.json` is Arendur as it is in the Arendur Rising
campaign. To work on a city, open the tool and import its file.

Everything in this repository is public.
