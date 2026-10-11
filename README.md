# Substrate releases

Nightly builds of Substrate: the macOS desktop app and the server package (`npx`/`npm` tarball).

- Download the newest build from [Releases](https://github.com/advantch/substrate-releases/releases).
- **macOS:** open the `.dmg` and drag **Substrate (Nightly)** to Applications. The first time, right-click the app and choose **Open**, because nightly builds are not notarized. After that the app checks this page for updates and installs them itself.
- **Server package:** `npm install -g <url of the .tgz asset>`, then `substrate serve`.

Nightly builds install beside the Alpha app and keep their own data in `~/.substrate-nightly`.
