# HomeZ Screen releases

The newest build of [HomeZ Screen](https://github.com/TaHo13), a custom home screen for Google TV / Android TV, for its built-in **Check for updates** (Customize → Update or remove…).

- `homez-screen-<version>.apk`: the app
- `latest.json`: its version, checksum and what changed
- `screensaver/`: HomeZ's own screen saver photos, shown until a TV has an album of its own (`list.json` names them). Photos from [Unsplash](https://unsplash.com), used under the Unsplash License.

A TV only installs an update that is newer and signed with the same key as the copy it already has. The app files are written by `app/release.sh`, the photos by `app/publish-saver.sh`.
