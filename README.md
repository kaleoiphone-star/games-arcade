# Games Arcade

One site for all our games. The home page (`index.html`) lists every game; each game lives in its own folder.

| Game | Folder |
| --- | --- |
| Debris Dynasty | `debris-dynasty/` |
| Joker Vault Deluxe | `joker-vault/` |
| Heilabrot (Icelandic crosswords) | `heilabrot/` |
| Quest 11: The Spellbound Citadel | `quest-11/` |
| 11+ Mastery Journey | `mastery-journey/` |
| Cognitive Conquest + Junior | links to https://cognitive-conquest.netlify.app (its own repo) |

There is no build step: Netlify publishes the repo as it is (see `netlify.toml`).

## Adding a game

1. Make a new folder, e.g. `my-game/`, and put the game's single HTML file in it as `index.html`.
2. Add a back link to the arcade somewhere in the game (`<a href="../">`).
3. Copy one of the `<a class="cart">` blocks in `index.html`, then change its link, picture, name and description.
