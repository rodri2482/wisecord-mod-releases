# WiseCord mod — releases

Public release feed and signed APK assets for the **WiseCord mod** self-updates.
The app checks `releases/latest` here from *Settings → App updates*.

- `wisecord-mod-vX.Y.Z.apk` — the APK the in-app updater downloads (updates over the
  currently installed build without a reinstall).
- `…-release-keystore.apk` — the same build signed with the release keystore, for clean
  installs on a new device. Installing it over a debug-signed build requires one
  uninstall first.

The mod's source (decompiled APK tree, relay, notes) stays in the private
[rodri2482/wisecord-mod](https://github.com/rodri2482/wisecord-mod) repo.