# Discord presence for Legato

A [Legato](https://github.com/legato-app/legato) plugin: shows what you play on your Discord profile, through the
Discord app on your PC and your own Discord application.

## Install

Download this repository (Code › Download ZIP) and unzip it, then in Legato: **Add-ons › Install a plugin…** › pick the
folder › Install. Legato shows the permissions it asks for before anything runs:

- `player:read`: what plays, so it can show it;
- `discord:presence`: can show any text and links on your Discord profile, through the Discord app on this PC;
- `ui`: its settings panel.

Its settings (your Discord application id, what to show, the buttons) are in the plugin's panel in Add-ons.

## Writing your own

This plugin uses the plugin API 2. The guide: [docs/plugins.md](https://github.com/legato-app/legato/blob/master/docs/plugins.md).
