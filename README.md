## Important Warning

Cordlink likely violates Discord's Terms of Service.

This project interacts with and modifies Discord client behavior in ways that may not be permitted under Discord's Terms. By downloading or using Cordlink, you accept the risk that your Discord account may be restricted, suspended, or otherwise affected.

Use it entirely at your own risk.

If Discord requests that this project, its releases, or related distribution files be removed, they will be taken down immediately.


# Cordlink

Cordlink is a Windows-only Fabric mod that adds positional Discord voice to Minecraft.

After linking your Discord account to your Minecraft account, Cordlink syncs Discord voice with in-game player positions so nearby players sound close and distant players sound far away.

## Why I Made This

I made Cordlink because I wanted Discord voice to feel more natural inside Minecraft without forcing people to switch to a separate voice chat system.

The goal was simple: keep using Discord, but make conversations feel like they are happening in the world around you.

## Project Status

Cordlink is an experimental personal project.

It is functional, but I am still deciding how far I want to take development and long-term public distribution. Things may change, break, or be removed without notice.

## Features

- Discord voice positioned in Minecraft 3D space
- Account linking by Minecraft UUID
- One-file install: only the mod `.jar` is needed
- Bundled native components extracted automatically on first sync

## Requirements

- Minecraft 1.21.3
- Fabric Loader
- Fabric API
- Java 21
- Windows
- Discord desktop app

## Download

Download the latest release here:

[GitHub Releases](https://github.com/Noted-Share/CordLink/releases)

## Installation

1. Download the latest `cordlink-*.jar`.
2. Put it into your `.minecraft/mods` folder.
3. Launch Minecraft with Fabric.
4. Make sure the Discord desktop app is running.
5. Link your Discord account with your Minecraft account through the Cordlink Discord bot.
6. Open the Cordlink screen in Minecraft and press `Sync`.
7. Leave and rejoin the voice channel after syncing.

## Important Notes

- Windows only
- Discord desktop only
- After pressing `Sync`, you must leave and rejoin the voice channel for it to work properly
- On first use, Cordlink extracts required native files into `.minecraft/cordlink`
- Some antivirus or security tools may react to native extraction or process injection behavior
- This is an unofficial project and is not affiliated with or endorsed by Discord, Mojang, Microsoft, or Fabric
- Use at your own risk

## Troubleshooting

### Sync says linked but voice is not positional

Leave and rejoin the Discord voice channel after pressing `Sync`.

### Sync fails

Check that:

- Discord desktop is running
- Your Discord account is linked correctly
- You are using the latest release
- Your antivirus did not block the mod or extracted native files

### No sound or wrong positioning

Try:

- restarting Minecraft
- restarting Discord
- syncing again
- rejoining the voice channel

## Support

If you need help or want to report a bug, join the support Discord:

[Discord Invite](https://discord.gg/7bGzPnNUjS)

## Source / License

This repository is used for release distribution and documentation only.

Source code is not published here.  
All rights reserved.

