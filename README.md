# MyJDownloader Extension MV3 Direct

> A community-maintained Manifest V3 fork of the MyJDownloader browser extension, designed to restore a smooth **"Download with JDownloader"** experience on modern Chromium-based browsers such as Brave and Chrome.

## Why this project?

The original **MyJDownloader** browser extension is based on **Manifest V2**, which is no longer supported by recent versions of Chromium-based browsers.

A community Manifest V3 port already exists, but several users (especially on Brave) have reported that the **right-click "Download with JDownloader"** action no longer behaves like the original extension.

Instead of sending links immediately to the connected JDownloader instance, the MV3 implementation relies on an injected in-page toolbar that may fail to appear depending on the website or browser restrictions.

This fork restores the original behavior.

## What has been changed?

This project is based on the existing Manifest V3 community implementation and introduces several improvements.

### Direct context menu sending

When selecting **"Download with JDownloader"** from the browser context menu:

* the selected link is sent directly to your connected MyJDownloader device;
* no in-page toolbar is required;
* no additional confirmation popup is needed;
* the workflow matches the original Manifest V2 extension.

### Better compatibility

This fork has been tested with modern Chromium-based browsers where the original extension can no longer be installed, including:

* Brave
* Google Chrome
* Chromium
* Microsoft Edge

## Features

* Login with your MyJDownloader account
* Automatic device detection
* Direct "Download with JDownloader" from the context menu
* LinkGrabber support
* Manifest V3 compatible
* No dependency on the injected page toolbar

## Installation

1. Download the latest release.
2. Extract the archive.
3. Open:

```
brave://extensions
```

or

```
chrome://extensions
```

4. Enable **Developer Mode**.
5. Click **Load unpacked**.
6. Select the extracted extension folder.
7. Sign in with your MyJDownloader account.

## Credits

This project is **not an official MyJDownloader extension**.

It is based on:

* the original MyJDownloader browser extension created by the JDownloader team;
* the community Manifest V3 migration project.

This repository simply continues that work by restoring the direct context-menu workflow that many users expected from the original extension.

All credit for the original project belongs to its respective authors.

## Disclaimer

This is an independent community fork.

It is not affiliated with or endorsed by the JDownloader or MyJDownloader teams.

## Contributing

Bug reports, feature requests and pull requests are welcome.

If this fork helped you continue using MyJDownloader on Brave or other Chromium browsers, feel free to leave a ⭐ on the repository.
