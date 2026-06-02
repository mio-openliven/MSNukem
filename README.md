# MS Nukem Client

Public download and release page for a test MS Nukem launcher build.

MS Nukem is a creator/server-specific launcher sample prepared for the Nuckem team. The practical goal is simple: a player downloads the launcher, enters a nickname, unlocks the correct mod build if needed, clicks **Download Mods**, and can start testing without manually installing modpacks or hunting for missing files.

Related creator link: [Nuckem on YouTube](https://youtube.com/@nuckem?si=8B60TLzrzN8HVh98)

## Project Status

This repository is a public client delivery channel, not the launcher source repository.

- **Useful now:** yes, as a test download/release page for players and testers.
- **Production-ready:** not fully. It is a beta delivery flow while the launcher, hosting, signing, and admin panel are still being hardened.
- **Main risk:** unsigned Windows builds may trigger SmartScreen warnings until the project has proper signing and reputation.
- **If needed:** the launcher and release process can be finished further for a cleaner production rollout.

## For Players

1. Download the latest launcher release from the **Releases** section.
2. Run the setup file.
3. Open the launcher and enter your Minecraft nickname.
4. Select **MS Nuckem** if it is not already selected.
5. Enter the build password from the server admin if the modpack is protected.
6. Click **Download Mods**, wait for the sync to finish, then click **Play**.

The intention is to remove the usual modpack headache: no manual folder copying, no guessing which version is current, and no private files listed in this public repository.

## Notes About Windows SmartScreen

Windows may warn about a new unsigned launcher build. This can happen with small independent tools before they build Microsoft reputation or receive a production code-signing certificate.

Only download files from this repository or the official project link given by the admin.

## What Is Not Stored Here

- No private source code.
- No server passwords.
- No personal tokens.
- No protected admin-panel data.
- No private customer configuration.

## Author Note

This repository exists as a clean public edge for a private server/client workflow. The private parts stay private; the player-facing download instructions stay simple.
