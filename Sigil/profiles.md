# Profiles

[Player index](README.md) · [Themes](themes.md) · [Commands](commands.md)

Your Sigil profile is your personal combination of theme plus overrides.

## Profile tools

| Command | What it does |
|---|---|
| `/sigil export` | Exports your current profile as a portable data string. |
| `/sigil import <data>` | Imports a profile string. |
| `/sigil resetall` | Clears your profile back to theme/default resolution. |

## Resolution order

Sigil resolves values in this general order:

1. your direct override
2. your active theme
3. the plugin defaults

That means a reset removes only your personal override. It does not delete the theme itself unless you clear the theme too.
