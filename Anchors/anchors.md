# Anchors & Utility Commands

[Player index](../README.md) · [Homes](homes.md) · [Warps & Portals](warps-portals.md) · [Random Teleport](rtp.md) · [TPA](tpa.md)

This section covers the core Anchors command tree plus the general travel utilities that sit outside homes, warps, RTP, and TPA. These commands handle saved anchor slots, forced saves, spawn travel, and back travel.

| Command | What it does |
|---|---|
| `/anchors help [main|homes|warps|rtp|tpa|admin]` | Shows the built-in help pages for the requested topic. |
| `/anchor help [main|homes|warps|rtp|tpa|admin]` | Alias of `/anchors help`. |
| `/anchors list` | Lists your saved anchor slots and coordinates. |
| `/anchors info` | Shows your resolved anchor and home slot counts plus anchor-related settings. |
| `/anchors save` | Forces an anchor save immediately if the server has that command enabled for you. |
| `/anchors back [slot]` | Teleports you to your latest anchor or a specific anchor slot. |
| `/anchors return [slot]` | Alias of `/anchors back`. |
| `/anchors goto [slot]` | Alias of `/anchors back`. |
| `/anchors cancel` | Cancels your pending teleport. |
| `/spawn` | Teleports you to the configured server spawn. |
| `/back` | Teleports you to your stored back location. |

## Notes

- `/anchor` is a direct alias of `/anchors`.
- Slot counts, cooldowns, and safety checks are server-configured.
