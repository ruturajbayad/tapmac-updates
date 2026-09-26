# TapMac Updates

Downloads and the auto-update feed for TapMac. The app's source code lives in a separate private repo.

## Install

1. Download the latest `TapMac-x.y.z.zip` from [Releases](https://github.com/ruturajbayad/tapmac-updates/releases/latest).
2. Unzip it and move **TapMac.app** into **Applications**.
3. Open TapMac. If macOS says it can't verify the app:
   1. Open **System Settings → Privacy & Security**.
   2. Scroll down to the message about TapMac and click **Open Anyway**.
   3. Confirm with your password or Touch ID.

You only need to do this once. After that, TapMac updates itself: use **Check for Updates…** in the menu bar, or let it check automatically.

## For maintainers

`appcast.xml` is the Sparkle feed that installed copies read. Don't edit it by hand: `Tools/release.sh` in the app repo adds each release to it.
