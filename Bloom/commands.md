# Bloom Commands

[Player index](README.md) · [Getting Started](getting-started.md) · [Actionbar and History](actionbar-history.md)

These are the normal Bloom player commands.

| Command | What it does |
|---|---|
| `/bloom stats` | Shows your stored totals and current-session stats. |
| `/bloom value <field>` | Shows one tracked value for yourself. |
| `/bloom top <field> [limit]` | Shows the server leaderboard for a supported field. |
| `/bloom recent [limit]` | Shows your recent payout ledger rows. |
| `/bloom actionbar <on\|off\|toggle>` | Controls whether Bloom shows payout gains in your actionbar. |

## Useful fields for `/bloom value`

- `total_earned`
- `daily_earned`
- `minute_earned`
- `session_earned`
- `blocks_broken`
- `blocks_placed`
- `mobs_killed`
- `items_crafted`
- `items_smelted`
- `playtime_rewards`
- `actionbar_enabled`

## Fields for category-specific minute tracking

- `minute_break`
- `minute_place`
- `minute_kill`
- `minute_craft`
- `minute_smelt`
- `minute_playtime`

## Leaderboard fields

`/bloom top` supports these fields:

- `total_earned`
- `daily_earned`
- `minute_earned`
- `blocks_broken`
- `blocks_placed`
- `mobs_killed`
- `items_crafted`
- `items_smelted`
- `playtime_rewards`
