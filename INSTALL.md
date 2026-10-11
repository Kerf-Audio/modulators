# Installing Kerf Modulators

Requires REAPER 6 or later. **Available now for Linux x86_64 (glibc 2.35+). macOS and Windows are coming soon.**

## With ReaPack (recommended)

This is the recommended way to install. You get updates automatically.

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

## Manual install

If you can't use ReaPack:

1. Download the file for your system from [Releases](../../releases):
   - Linux: `reaper_kerf_modulators.so`
2. In REAPER, choose **Options > Show REAPER resource path in explorer/finder**.
3. Copy the file into the `UserPlugins` folder there.
4. Restart REAPER.

## Upgrading from a beta

If you installed a beta by hand, delete the old file from `UserPlugins`
(`reaper_kerf_modulators.so`)
**before** installing with ReaPack. Otherwise REAPER may load two copies.

## Uninstalling

- **ReaPack:** Browse packages, right-click Kerf Modulators, **Uninstall**, Apply, restart REAPER.
- **Manual:** delete the file from `UserPlugins` and restart REAPER.

Your projects keep their modulator data, but it does nothing without the extension.
