# Rift Imaginators Client

An unofficial Windows client and launcher for Skylanders Imaginators (Wii U US v0).

## Download and play

1. Open [Releases](https://github.com/Shruude/rift-imaginators-client/releases/latest) and download **Rift-Launcher-0.2.0.zip**.
2. Extract the entire ZIP into its own writable folder. Run **Rift-Launcher.exe**.
3. Choose your game's extracted **.rpx** and save folder in Settings. Install the client, then select **Play**.

Existing 0.1.0 users: close only the launcher and extract the complete 0.2.0 ZIP over the existing launcher folder. Keep your local settings and Data folders. This one-time upgrade enables future launcher updates.

## Updates

The launcher checks this public release channel when opened. New client builds change Play to **Update**. New launcher builds change it to **Update & Restart**. If both are available, update the launcher first, then the client.

Launcher updates use separate version folders and confirm that the new interface starts. A failed startup returns to the previous launcher; an interrupted restart is recovered when you reopen the desktop shortcut. Game paths, settings, saves, figures, and the installed client stay intact. Launcher-only changes do not download the game client again.

The new blue-and-gold portal icon is included. Use **Settings → Desktop shortcut** to create a shortcut that follows future icon updates. The game can keep running while the launcher updates. Client installation and rollback still require closing the game.

## Included client changes

Client **0.1.0** is unchanged in this release:

- Keyboard prompts and configurable controls, a denser Rift character library, and mouse-wheel navigation.
- Rift Trainer rewards and ability unlocks.
- Rift Momentum: direct Kaos boss fight; three consecutive clean hits restore health.
- Esc Settings, with the emulator menu hidden during supported gameplay.

The Esc menu captures input but does not pause the game. This is an early build. Boss entry, combat rewards, and returning to the hub were tested; full boss victory has not been play-tested. Online co-op and a bot teammate are not included.

Game files, console fonts, saves, and figure data are supplied separately and are not included in downloads.

## Source and licenses

Download **Rift-Source-0.2.0.zip** from the matching release for launcher and client sources, licenses, icon artwork, and credits. Choose the named Rift-Source asset; GitHub's automatic source archive contains this repository's documentation.

The emulator is based on [Rift Barebones](https://github.com/Swanikins/Rift-Barebones-Releases) and Cemu, with MPL-2.0 source and notices included. The launcher uses the MIT license. See bundled third-party notices for portrait credits. The portal icon is original AI-generated artwork for this unofficial launcher.

This project is not affiliated with Activision, Toys for Bob, Nintendo, or upstream emulator projects.
