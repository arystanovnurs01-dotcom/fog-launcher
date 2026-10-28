# Fog Launcher

Fog Launcher 1.3.7 for Windows x64 (Minecraft Java Edition 1.21.11 + Fabric).

## Website

- Live demo: <https://arystanovnurs01-dotcom.github.io/fog-launcher/>
- Standalone preview: <https://arystanovnurs01-dotcom.github.io/>
- Public custom domain: `fogvisual.is-a.dev` is **not connected** — the is-a.dev
  pull request #58677 was closed/denied, so no `CNAME` is published.
- The public demo uses browser-only demo authentication. The full server version
  with Express + PostgreSQL is not deployed publicly yet.

## Download

- [FogLauncher.exe](https://arystanovnurs01-dotcom.github.io/fog-launcher/FogLauncher.exe) — one clean file, recommended.
- [Update manifest](https://arystanovnurs01-dotcom.github.io/fog-launcher/latest.json).
- [GitHub release v1.3.7](https://github.com/arystanovnurs01-dotcom/fog-launcher/releases/tag/v1.3.7) — fallback asset.

SHA-256 for the exe:

`81427C09860BC48EDA8162306CB4A1BB33A9535671057B4C53C1C6043E0A553C`

Size: 99 254 188 bytes.

## Auto-update

The launcher checks the Pages manifest on startup and offers the newest
`FogLauncher.exe`. The `update.json` shipped with the launcher points to
`https://arystanovnurs01-dotcom.github.io/fog-launcher/latest.json`.

## Clean package

The release contains only the launcher, the bundled mods, licenses and
`update.json`. It does **not** contain accounts, profiles, skins, logs or
personal settings. The public page does not offer a ZIP archive or
source-code links.

## What's new in 1.3.7

- Six launcher styles (Moonlit Night, Light Breeze, Forest Fog, Neon, Sunset,
  Lunar Clouds) now recolor the whole interface: sidebar, top/bottom bars,
  cards, buttons, fields, dialogs, overlays and wallpaper.
- The profile, sidebar and account cards show the skin currently equipped on
  the player; the Fog avatar is only a fallback when no skin render exists.
- Style changes apply immediately without restarting the launcher.
- Current Fog Visuals 1.0 (patched): AutoSwap, HitFx, Lyrics, cosmetics,
  emotes, Dynamic Island and combat effects.
- Clean `FogLauncher.exe` download without a version suffix or `(1)`,
  SmartScreen guidance and SHA-256 verification on the site.
