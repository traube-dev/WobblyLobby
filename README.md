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
- Invite code hidden by default (`******`), with reveal/copy buttons next to it - the base game shows the raw code on screen at all times, which means anyone who can see your screen (streams, screen shares, a photo of your monitor) can join your lobby whenever they want, invited or not. Hiding it by default and only revealing it on click closes that off

## Requirements
- Wobbly Life (via Steam)
- BepInEx 5.x
- [tdToolz](https://github.com/traube-dev/tdToolz)

## Installation
See [traube.dev/docs](https://traube.dev/docs.html) for the general BepInEx + mod install walkthrough.
