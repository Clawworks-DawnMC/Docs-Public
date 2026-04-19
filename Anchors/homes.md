# Homes

[Player index](../README.md) · [Anchors & Utility](anchors.md) · [Warps & Portals](warps-portals.md) · [Random Teleport](rtp.md) · [TPA](tpa.md)

Homes are named personal teleport points. Anchors supports normal homes, shared homes, invite-based access, visibility modes, and optional waypoints that can be exposed to other players.

| Command | What it does |
|---|---|
| `/sethome <name>` | Creates or updates one of your homes at your current location. |
| `/home <name>` | Teleports you to one of your own homes. |
| `/home help` | Shows home command help. |
| `/home visit <player> <home>` | Teleports you to another player's shared home when you are allowed to visit it. |
| `/home public <home>` | Sets one of your homes to public visibility. |
| `/home private <home>` | Sets one of your homes to private visibility. |
| `/home invited <home>` | Sets one of your homes to invited-only visibility. |
| `/home invite <home> <player>` | Adds a player to a home's invite list. |
| `/home uninvite <home> <player>` | Removes a player from a home's invite list. |
| `/home invites <home>` | Lists the players invited to a home. |
| `/home waypoint <home> <on\|off>` | Enables or disables the waypoint flag on a home. |
| `/delhome <name>` | Deletes one of your homes. |
| `/homes` | Lists your homes and your current home limit. |
| `/homes list` | Lists your homes and your current home limit. |
| `/homes help` | Shows homes command help. |
| `/homes rename <old> <new>` | Renames one of your homes if that feature is available to you. |
| `/homes waypoints` | Lists the shared waypoints you can currently access. |

## Notes

- Shared-home access depends on the home's visibility and invite state.
- Home limits, world restrictions, cooldowns, and safety checks are server-configured.
