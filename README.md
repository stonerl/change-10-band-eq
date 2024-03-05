# Change 10-Band EQ

This is a simple shortcut for macOS that changes the EQ settings in
[SoundSource®](https://rogueamoeba.com/soundsource/) based on the genre of the
song currently playing in the Music app.

## Requirements

- [Actions](https://apps.apple.com/app/id1586435171) for Shortcuts

- [nowplaying-cli](https://github.com/kirtan-shah/nowplaying-cli)

```bash
brew install nowplaying-cli
```

## Installation

1. Copy the `EQ-Settings.json` file to your computer,
e.g., to the iCloud Shortcuts folder.
2. Double-click the `Change 10-Band EQ.shortcut` file
to add it to the Shortcuts app.
3. Select the `EQ-Settings.json` file when asked for it.
4. Open the Shortcuts app and run it manually, once while playing music.
5. When prompted, select `Always allow` in every dialog.

## Usage

The shortcut is added to the `Services Menu`, you can either run it manually
or bind it to a keyboard shortcut.

You can also use an app like [Shortery](https://apps.apple.com/app/id1594183810)
to automate the execution of the shortcut. E.g. whenever the Music app is in focus
execute the shortcut.

## Additional information

The genre list was compiled from
[Apples Music Style Guide](https://help.apple.com/itc/musicstyleguide/#/itc784423802).
