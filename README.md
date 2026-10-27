# Fog Launcher

Fog Launcher 1.3.5 for Windows x64 (Minecraft Java Edition 1.21.11 + Fabric).

## Website

- Live demo: <https://arystanovnurs01-dotcom.github.io/fog-launcher/>
- Public domain: <https://fogvisual.is-a.dev/> (is-a.dev registration pending)
- The public demo uses browser-only demo authentication. The full server version
  with Express + PostgreSQL is in the [Fog_Launcher_Full_Project.zip](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases/download/v1.3.5/Fog_Launcher_Full_Project.zip) release asset.
- Standalone preview: [Fog_Launcher_Preview.html](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases/download/v1.3.5/Fog_Launcher_Preview.html).

## Download

- [FogLauncher-1.3.5.exe](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases/latest/download/FogLauncher-1.3.5.exe) — one file, recommended.
- [FogLauncher-1.3.5-win-x64.zip](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases/latest/download/FogLauncher-1.3.5-win-x64.zip) — portable package with `update.json` and licenses.
- [All releases](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases)

SHA-256 for the exe:

`EAE2389B6DE1F14A47B4BD2CB5C78334BB50C6FE4F4E82EF007005D15F5551BF`

## Auto-update

The launcher checks GitHub Releases on startup and offers the newest
`FogLauncher-<version>.exe`. The `update.json` shipped with the launcher already
contains `githubRepo` and a fallback `manifestUrl`, so no setup is needed.

## Clean package

The release contains only the launcher, the bundled mods, licenses and
`update.json`. It does **not** contain accounts, profiles, skins, logs or
personal settings.

## What's new in 1.3.5

- AutoSwap: swap totem / player head / sphere to the left hand without throwing a pearl.
- Hit Effects: no circular flash; the added non-circular effects remain.
- Automatic updates via GitHub Releases.