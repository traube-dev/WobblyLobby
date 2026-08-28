---
name: WobblyLobby
tagline: Lobby size, custom names, and travel controls for your multiplayer games
dependencies: [https://github.com/traube-dev/tdToolz]
thumbnail: thumbnail.png
---

WobblyLobby extends the multiplayer lobby with settings the base game doesn't expose - lobby size, a custom lobby name template, host-side control over rocket/scene travel requests, and quick invite-code buttons on the multiplayer menu.

## Features
- Customizable lobby size (1 up to unlimited)
- Customizable lobby name template - supports `%{Player.Name}` as a placeholder and rich-text color tags
- Host-only toggle for whether non-host players may request rocket/scene travel at all
- Host-only toggle to launch travel immediately instead of waiting for every player to accept
- Reveal/copy buttons added next to the invite code on the multiplayer menu

## Requirements
- Wobbly Life (via Steam)
- BepInEx 5.x
- [tdToolz](https://github.com/traube-dev/tdToolz)

## Installation
See [traube.dev/docs](https://traube.dev/docs.html) for the general BepInEx + mod install walkthrough.
