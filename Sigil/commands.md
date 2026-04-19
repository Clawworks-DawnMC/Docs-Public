# Commands

[Player index](README.md) · [Themes](themes.md) · [Profiles](profiles.md)

These are the normal player-facing Sigil commands.

| Command | What it does |
|---|---|
| `/sigil help` | Shows the built-in help page. |
| `/sigil theme` | Shows your active theme. |
| `/sigil theme list [category]` | Lists themes you can use. |
| `/sigil set theme <theme>` | Sets your active theme. |
| `/sigil set color <slot> <value>` | Sets one color override. |
| `/sigil set symbol <slot> <value>` | Sets one symbol override. |
| `/sigil get color <slot>` | Shows the resolved color value for one slot. |
| `/sigil get symbol <slot>` | Shows the resolved symbol value for one slot. |
| `/sigil get gradient <slot> <text>` | Renders sample text using the resolved gradient. |
| `/sigil inspect` | Shows your resolved values and their sources. |
| `/sigil reset <color\|symbol> <slot>` | Removes one override. |
| `/sigil resetall` | Resets your full profile. |
| `/sigil preview` | Shows your configured preview lines. |
| `/sigil export` | Exports your current profile as data. |
| `/sigil import <data>` | Imports a profile string. |
| `/ui ...` | Alias of `/sigil ...`. |

## Color slots

- `accent`
- `text`
- `title`
- `border`
- `info`
- `action`

## Symbol slots

- `accent`
- `border`
- `info`
- `action`
- `divider`
- `bullet`
