# Installing Kerf Modulators

Requires REAPER 6 or later, on macOS 11+, Windows 10 or 11 (x64), or Linux x86_64.

## With ReaPack (recommended)

This is the way to install on every platform, and the only way on macOS. You get
updates automatically.

1. Install [ReaPack](https://reapack.com) if you don't have it.
2. In REAPER, open **Extensions > ReaPack > Import repositories...**
3. Paste this URL and click OK:
   ```
   https://raw.githubusercontent.com/Kerf-Audio/reapack/main/index.xml
   ```
4. Open **Extensions > ReaPack > Browse packages**, search for **Kerf Modulators**,
   right-click it and choose **Install**, then click **Apply**.
5. Restart REAPER.
6. Open the panel from **Extensions > Modulators: Show/hide panel**.

To try fixes before they reach everyone, right-click Kerf Modulators in
**Browse packages** and enable **pre-releases** for it.

## Manual install (Windows and Linux only)

On macOS, install with ReaPack. On Windows or Linux, if you can't use ReaPack:

1. Download the file for your system from [Releases](../../releases):
   - Windows: `reaper_kerf_modulators-x64.dll`
   - Linux: `reaper_kerf_modulators.so`
2. In REAPER, choose **Options > Show REAPER resource path in explorer/finder**.
3. Copy the file into the `UserPlugins` folder there.
4. Restart REAPER.

## Upgrading from a beta

If you installed a beta by hand, delete the old file from `UserPlugins`
(`reaper_kerf_modulators.dylib`, `reaper_kerf_modulators-x64.dll` or
`reaper_kerf_modulators.so`, and on macOS any older `reaper_modular*.dylib`)
**before** installing with ReaPack. Otherwise REAPER may load two copies.

## Uninstalling

- **ReaPack:** Browse packages, right-click Kerf Modulators, **Uninstall**, Apply, restart REAPER.
- **Manual (Windows and Linux):** delete the file from `UserPlugins` and restart REAPER.

Your projects keep their modulator data, but it does nothing without the extension.
