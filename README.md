# Project Phoenix

A personal Minecraft: Java Edition launcher — a fork of
[Horizon](https://github.com/horizon-rust/horizon) (MIT), customized for my own use.

## What this is

- The same open-source launcher engine as Horizon: it installs and prepares the game,
  manages instances, mods, packs, servers and screenshots.
- Sign-in uses my own Azure app registration (device-code flow, scopes
  `XboxLive.signin offline_access`), never Horizon's — per Horizon's
  [forking policy](https://github.com/horizon-rust/horizon/blob/main/docs/forking.md).
- Customizations: a user-editable `custom.toml` override file (branding, theme,
  promotions, Azure client ID), the self-update to official builds is disabled, and
  Horizon's promotional cards and links are hidden.

## Credits

- Upstream project: [Horizon](https://github.com/horizon-rust/horizon) by
  [ludovic111](https://github.com/ludovic111) and contributors, MIT licensed.
- All credit for the launcher engine, the game client and the server belongs to the
  Horizon project; this repository only carries my configuration changes.
