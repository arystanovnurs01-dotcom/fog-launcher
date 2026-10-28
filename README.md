# Fog Launcher

Fog Launcher 1.3.6 for Windows x64 (Minecraft Java Edition 1.21.11 + Fabric).

## Website

- Live demo: <https://arystanovnurs01-dotcom.github.io/fog-launcher/>
- Public domain: пока нет. Заявка на `fogvisual.is-a.dev` отклонена is-a.dev
  (root-домены только для портфолио разработчика).
- The public demo uses browser-only demo authentication. The full server version
  with Express + PostgreSQL is not deployed publicly yet.
- Standalone preview: <https://arystanovnurs01-dotcom.github.io/>.

## Download

- [FogLauncher.exe](https://arystanovnurs01-dotcom.github.io/fog-launcher/FogLauncher.exe) — one clean file, recommended.
- [Update manifest](https://arystanovnurs01-dotcom.github.io/fog-launcher/latest.json).
- [GitHub release v1.3.6](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases/tag/v1.3.6) — fallback asset.

SHA-256 for the exe:

`BC05F1661147C01A223759E04F799A55B35C75D89B4256484D482B7CB68EB01A`

Size: 93 107 405 bytes.

## Auto-update

The launcher checks the Pages manifest on startup and offers the newest
`FogLauncher.exe`. The `update.json` shipped with the launcher points to
`https://arystanovnurs01-dotcom.github.io/fog-launcher/latest.json`.

## Clean package

The release contains only the launcher, the bundled mods, licenses and
`update.json`. It does **not** contain accounts, profiles, skins, logs or
personal settings. The public page no longer offers a ZIP archive or
source-code links.

## What's new in 1.3.6

- Six launcher styles: Moonlit Night, Light Breeze, Forest Fog, Neon, Sunset,
  Lunar Clouds.
- One fog-and-moon avatar across the launcher.
- Clean `FogLauncher.exe` download without a version suffix or `(1)`.
- SmartScreen guidance and SHA-256 verification on the site.
- Fog Visuals 1.7.0: realistic blood droplets and ground puddles, new kill,
  totem, Target ESP, swing trail and jump circle effects.
- Redesigned mod menu and HUD in the Fog palette.
