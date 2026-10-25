# Plugins Boss — downloads

Plugins Boss is a Windows app that keeps track of your audio plugins: what's installed, which copies your DAWs (Studio Pro, Cakewalk Sonar) actually load, duplicates and old versions, vendor updates, and a safe quarantine with undo.

## Download

Get **`PluginsBoss-Setup-<version>.exe`** from the [latest release](../../releases/latest) and run it (Windows 10/11, 64-bit, no admin rights needed).

- Windows SmartScreen may say "Windows protected your PC" because the installer isn't code-signed yet: click **More info › Run anyway**.
- **Updating:** close Plugins Boss and run the new installer. It updates in place and keeps your scan results and settings. Plugins Boss shows a banner when a new version is out.

## About this repository

This repository only hosts the installers and `latest.json`, which Plugins Boss reads to see whether a newer version exists. The check sends nothing about you or your PC, and can be turned off with `"check_app_updates": false` in `%LOCALAPPDATA%\Plugins Boss\config.json`.
