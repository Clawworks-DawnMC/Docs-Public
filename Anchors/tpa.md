# TPA

[Player index](README.md) · [Anchors & Utility](anchors.md) · [Homes](homes.md) · [Warps & Portals](warps-portals.md) · [Random Teleport](rtp.md)

Anchors TPA is a queued teleport request system. You can send requests, accept or deny incoming requests, cancel outgoing requests, or toggle automatic acceptance.

| Command | What it does |
|---|---|
| `/tpa <player>` | Sends a request to teleport to another player. |
| `/tpahere <player>` | Sends a request asking another player to teleport to you. |
| `/tpaccept [player]` | Accepts the oldest incoming request, or a specific player's request if a name is supplied. |
| `/tpadeny [player]` | Denies the oldest incoming request, or a specific player's request if a name is supplied. |
| `/tpacancel` | Cancels your outgoing teleport request. |
| `/tpaautoaccept` | Toggles automatic acceptance of incoming teleport requests if that feature is available to you. |
