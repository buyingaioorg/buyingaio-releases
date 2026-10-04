# BuyingAIO

Manage retailer orders, track shipments and payouts, and reconcile your purchases
in one desktop app.

## Download

**[Download the latest version](https://github.com/buyingaioorg/buyingaio-releases/releases/latest)**

| Computer | Download |
| --- | --- |
| Windows 10/11 (64-bit) | `BuyingAIO-Setup-<version>.exe` |
| Mac with Apple silicon (M1 or newer) | `BuyingAIO-<version>-arm64.dmg` |
| Mac with an Intel processor | `BuyingAIO-<version>-x64.dmg` |
| Linux, 64-bit Intel/AMD | `BuyingAIO-<version>-x86_64.AppImage` |
| Linux, 64-bit ARM | `BuyingAIO-<version>-arm64.AppImage` |

## Install

- **Windows:** run the installer. If Windows SmartScreen shows "Windows protected
  your PC", click **More info**, then **Run anyway**.
- **macOS:** open the DMG, drag BuyingAIO into Applications, then open it. If macOS
  says it cannot verify the app, open **System Settings > Privacy & Security** and
  click **Open Anyway** (once). If macOS asks to allow access to
  "BuyingAIO Safe Storage", enter your password and click **Always Allow**.
- **Linux:** make the AppImage executable (`chmod +x`) and keep it at a fixed path
  you can write to, for example `~/Applications/BuyingAIO.AppImage`, then run it.

## Updates

- **Windows and Linux:** BuyingAIO updates itself. It downloads new versions in the
  background and installs them when you restart, after running imports, syncs and
  purchases finish.
- **macOS:** BuyingAIO tells you when a new version is available. Download it from
  this page and replace BuyingAIO in Applications.

## Upgrading from an older version

BuyingAIO 1.1.x and the 2.0.1 preview cannot update themselves to 1.0.0 or later.
Install the new version once by hand:

1. Finish any imports, syncs or purchases, then quit BuyingAIO.
2. Back up your data folder (see below).
3. Install the new version over the old one: replace BuyingAIO in Applications
   (macOS), run the installer (Windows), or replace the AppImage (Linux).
4. Open BuyingAIO. Your orders, settings, profiles and retailer sign-ins are kept,
   and BuyingAIO saves its own backup in the data folder (`backups/`) before
   upgrading. Some services may ask you to sign in again.

Do not open the old version again afterwards: it may not understand data updated
by the new version. To go back, restore your data backup together with the old app.

## Your data

| Computer | Data folder |
| --- | --- |
| macOS | `~/Library/Application Support/buyingaio` |
| Windows | `%APPDATA%\buyingaio` |
| Linux | `~/.config/buyingaio` |

Uninstalling BuyingAIO does not delete this folder. Do not delete it unless you
mean to erase all of your BuyingAIO data.

## Verify downloads

Every release includes `DOWNLOAD-SHA256SUMS` with the SHA-256 checksum of each
download.
