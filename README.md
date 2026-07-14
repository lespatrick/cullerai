# Culler.ai

Culler.ai is a native macOS application designed for photographers to automate photo selection (culling). It helps you sort through large shoots quickly by clustering near-duplicate photos, detecting photo defects, and automatically applying star ratings.

## Features

- **Automated Culling**: Instantly rate and filter photos using a 5-star rating system.
- **Smart Stacking**: Groups near-duplicate shots so you can easily view similar photos together and select the best ones.
- **Defect Detection**: Identifies motion blur, closed eyes, and aesthetic quality.
- **Seamless Integration**: Fully compatible with professional photography suites (Capture One, Lightroom) through standard XMP sidecar files.
- **100% Private**: All processing is done locally on your device with no cloud dependencies.

## Installation & Running

1. Download **[Culler.ai.dmg](https://github.com/lespatrick/cullerai/raw/refs/heads/main/Culler.ai.dmg)** from this repository.
2. Open the DMG and drag **Culler.ai.app** to your `/Applications` directory.

### macOS Gatekeeper Security Notice

Since this is an early alpha release distributed directly, macOS may show a warning when opening the app for the first time. You can register a system exemption by choosing one of these methods:

- **Option 1 (Recommended)**: Right-click (or Control-click) **Culler.ai.app** in Finder, select **Open**, and click **Open** on the confirmation prompt.
- **Option 2**: Open the app once. When blocked, go to **System Settings > Privacy & Security**, scroll down to the Security section, and click **Open Anyway**.
- **Option 3 (Terminal)**: Clear the quarantine flag by running the following command in Terminal:
  ```bash
  xattr -r -d com.apple.quarantine /Applications/Culler.ai.app
  ```

## Documentation

For full guides and information, check out the [documentation page](https://lespatrick.github.io/cullerai/).

## License

Copyright © 2026 Culler.ai. All rights reserved.
