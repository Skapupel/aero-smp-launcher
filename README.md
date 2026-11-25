# Aero SMP Launcher

A private, non-commercial Windows launcher for **Aero SMP**, our modded community server
(Minecraft: Java Edition 1.21.1, NeoForge).

> Status: in development.

## What it does

- **Signs players in with their own Microsoft account** and checks that they own
  Minecraft: Java Edition before the game can start.
- **Keeps the modpack up to date automatically.** Before each launch it checks our file server
  and downloads only the files that changed (mods, configs, resource packs, shaders).
- **Lets players choose optional content**, such as client-side mods, resource packs and shaders.
- **Adds our server to the in-game server list**, so players can join straight away.
- **Settings** for install folder, memory (RAM) and Java arguments.

## Authentication and ownership

The launcher uses the official Microsoft / Xbox Live sign-in flow to get the player's
Minecraft access token. It **never bypasses** authentication, ownership or license checks,
and it only launches the game for signed-in players who own Minecraft: Java Edition.
Our server runs in online mode, so every player is verified.

The launcher does not collect, store or share passwords. Sign-in happens on Microsoft's own
login page; the launcher only keeps the login tokens on the player's own computer so they
don't have to sign in every time.

## Who it's for

Members of the Aero SMP community. It is not sold, has no ads, and is not affiliated with
or endorsed by Mojang Studios or Microsoft.

## Platform

Windows 10 / 11.

## Contact

Questions or issues: open an issue in this repository.
