# Actionbar and History

[Player index](README.md) · [Getting Started](getting-started.md) · [Commands](commands.md)

Bloom can show recent payout gains in your actionbar and can also show you a short reward history.

## Actionbar

The actionbar is the small message area above your hotbar.

Example format:

```text
+0.25 Bits
```

Your server can change:

- whether actionbars are enabled globally
- how often they flush
- the text format
- the currency label

### Actionbar commands

| Command | What it does |
|---|---|
| `/bloom actionbar on` | Enables your personal actionbar |
| `/bloom actionbar off` | Disables your personal actionbar |
| `/bloom actionbar toggle` | Switches your current state |
| `/bloom actionbar` | Toggles without specifying a mode |

If actionbars are disabled globally, your personal toggle cannot override that.

## Recent payout history

`/bloom recent [limit]` shows recent reward rows such as:

- category
- action key
- amount
- world
- time

This only works when the server stores Bloom's payout ledger. If the server disables ledger storage, recent history may be empty.
