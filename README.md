# Game Queue Notifier

**Your queue. Your cue.**

Game Queue Notifier (GQN) is a free Windows app that alerts you when a configured event occurs in a game or application. Use taskbar flashing or a visual change in a selected window area to receive a notification when your queue is ready or a match starts.

[**Download v1.0.0 for Windows**](https://game-queue-notifier.pages.dev/downloads/Game-Queue-Notifier-v1.0.0-Windows.zip) · [Website](https://game-queue-notifier.pages.dev/) · [GitHub Releases](https://github.com/Woltano/Game-Queue-Notifier/releases) · [Report an issue](https://github.com/Woltano/Game-Queue-Notifier/issues)

![Game Queue Notifier 1.0.0 showing the Detection tab in English](https://game-queue-notifier.pages.dev/assets/gqn-detection-en.webp)

## Features

- **Two detection methods:** react to Windows taskbar flashing or changes in a selected part of an application's window.
- **Optional second stage:** configure a separate second event, using the same application or a different one.
- **Custom alerts:** use the included sounds or import your own WAV and MP3 files, adjust alert volume and enable Windows notifications.
- **Game audio controls:** configure when the selected application's audio is muted or restored.
- **Profiles and presets:** save settings for individual applications and keep reusable configurations.
- **Game-start automation:** use an optional background helper to perform saved actions when a configured application starts, including launching a script or program you choose.
- **Personalization:** choose a theme, an accent color and one of 12 interface languages.
- **Activity Log and diagnostics:** review detected events and copy diagnostic information when you need help.

## Requirements and installation

- Windows 10 or Windows 11.
- Microsoft .NET Framework 4.8.

1. Download `Game-Queue-Notifier-v1.0.0-Windows.zip` using the download link above. Official releases are also listed in this repository's **Releases** section.
2. Extract the ZIP and run `GameQueueNotifier-Setup-v1.0.0.exe`.
3. Open Game Queue Notifier from the Start menu or its desktop shortcut.

The installer installs GQN for the current Windows user without requiring administrator rights. The current installer is not digitally signed, so Windows may display an unknown-publisher or reputation warning.

## Quick start

1. Start your game or application, then select it on the **Detection** tab.
2. Choose a detection method. For visual detection, select a small, stable area and capture its baseline while waiting for the event.
3. Click **START MONITORING**.

Enable **Stage 2** only if you need a second event. Hover over an option for an explanation, or open **Info** for the user guide.

## Compatibility and audio

Taskbar detection works when the selected application sends Windows taskbar-flashing notifications. Visual detection depends on usable window capture; some games stop rendering while minimized. Check the capture result and test your configuration with your game. After changing the monitored area, capture a new baseline.

GQN's audio-output selection applies to WAV sounds. MP3 playback uses the Windows default output. After reconnecting a headset, click **Refresh audio**.

## Privacy and interaction with games

GQN works locally. It contains no telemetry, advertising analytics or automatic crash-report uploads.

It uses standard Windows information about windows, processes, taskbar notifications and audio devices. Visual detection captures the selected window's image. GQN **does not modify game files, read or write game-process memory, inject code, or control keyboard or mouse input in games**.

Settings, profiles, imported sounds, saved baseline images and helper logs are stored locally. Diagnostics may include application names and local paths; review them before sharing. The optional helper can continue running after the main window closes when automation is enabled.

See [PRIVACY.txt](PRIVACY.txt) for the full privacy information. Compatibility with every game or anti-cheat system is not guaranteed.

## Interface languages

English, Polish, German, Spanish, French, Brazilian Portuguese, Turkish, Japanese, Korean, Russian, Simplified Chinese and Traditional Chinese.

## Help and feedback

Use [GitHub Issues](https://github.com/Woltano/Game-Queue-Notifier/issues) to report a problem or suggest an improvement. Include your GQN version, Windows version, what you expected and the steps that reproduce the problem. You can attach screenshots or reviewed diagnostic text when useful.

## License and author

Created by **Woltano**. Free to download and use under the terms in [LICENSE.txt](LICENSE.txt). This project uses a custom license; please read it before redistributing the application or reusing its code. See [COPYRIGHT.txt](COPYRIGHT.txt) for authorship information.

If GQN helps you, you can [buy me a coffee](https://buymeacoffee.com/woltano).

Copyright (c) 2026 Woltano. All rights reserved.
