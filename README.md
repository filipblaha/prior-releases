# Prior releases

Signed release files for invited testers of Prior, a desktop champion select assistant for macOS
and Windows. This repository holds no source code.

**Download:** open [Releases](../../releases/latest) and pick the macOS `.dmg` (Apple Silicon and
Intel) or the Windows `-setup.exe`. After the first install the app updates itself: it shows
"Install and restart" when a new version is out.

**Coming from Machine LoLing:** Prior is its new name (from 0.2.0). It installs as a separate app,
so remove the old one: in Machine LoLing turn off **Start at login** in Settings, quit it from the
tray menu, then uninstall it (macOS: move `Machine LoLing.app` to the Bin; Windows: **Settings >
Apps > Installed apps > Machine LoLing > Uninstall**). Your pool does not carry over.

**Windows:** the installer is not code-signed yet. If SmartScreen says "Windows protected your
PC", choose **More info → Run anyway**. The macOS app is signed and notarized by Apple.

**Update check:** the app downloads `latest.json` from the latest release here, at start and every
6 hours (it can be turned off in Settings). The request carries no usage data, account or device
ID; GitHub sees your IP address, as with any download. Every update is signed, and the app refuses
files without the project's signature.

Prior isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or
anyone officially involved in producing or managing Riot Games properties. Riot Games, and all
associated properties are trademarks or registered trademarks of Riot Games, Inc.
