# Ward Builder

An abstract city map builder for tabletop RPG cities: wards and the borders between them, grouped into districts,
controlled by factions, with power centres, points of interest, alliances and rivalries.

Open it at **https://bahnegork.github.io/Ward-Builder/** (or open `index.html` straight from disk). It is one
self-contained HTML file with no external dependencies.

## Saving your work

The tool autosaves **only in your own browser**, separately for each address you open it from. Browser storage
can be cleared or lost, so save to GitHub (below) or export regularly:

- **File → Export map JSON** saves the whole city as a JSON file.
- **File → Import map JSON** loads one back (this replaces the city currently open).

## Cities on GitHub

A city is kept as `cities/<city>/<version>.json` in a GitHub repository, one file per version of a city. Each
campaign that uses a city has its own version, e.g. `cities/arendur/arendur-rising.json` is Arendur as it is in the
Arendur Rising campaign. The file's `city` block says which city and version it is (`id`, `name`, `version`, and
optionally `campaign` and `year`).

Under **File → GitHub**:

- **Open city from GitHub...** lists the cities in the repository and opens one.
- **Save to GitHub...** saves the open city to its file, with an optional note. Every save is a commit.
- **History...** lists the saves of the open city's file; open any of them to see the city as it was then.
  Saving an older state makes it the newest one; nothing in between is lost.
- **City details...** sets the city's name, campaign, year and version name.
- **Clone to new campaign...** turns the open city into a new version (a new file) for another campaign or era.
- **GitHub settings...** sets the repository, branch and token.

**Which repository:** opened from GitHub Pages (`owner.github.io/repo/`), the tool reads the repository it is served
from, so a copy of the tool in your own repository reads your own cities. Opened anywhere else, name the repository
under GitHub settings.

**Reading** a public repository needs nothing. **Saving** needs a
[fine-grained token](https://github.com/settings/personal-access-tokens/new) limited to that one repository, with
*Contents: Read and write*. The token is stored only in your browser.

Everything in this repository is public.
