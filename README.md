# Gloss releases

Windows x64 installers and signed automatic-update metadata. Application source code is kept in a separate private repository.

## Install

1. Download the newest `Gloss_*_x64-setup.exe` from [Releases](https://github.com/whiank/gloss-releases/releases/latest).
2. Exit the old Gloss from its system-tray menu, then run the installer.
3. Launch the installed Gloss. In Settings > General > About and updates, check for updates.

Version 0.1.0 needs this first manual installation. Later versions check periodically and offer Download and install; installation requires a click. Old manually copied executables and shortcuts still launch the old copy.

The `.sig` and `latest.json` assets are used by the application's updater. Update signatures are separate from Windows Authenticode; the installer currently has no Windows publisher certificate.