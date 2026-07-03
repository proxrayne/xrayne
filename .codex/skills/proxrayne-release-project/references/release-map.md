# Proxrayne Release Repository Map

## Role

`xrayne` is the public release/install repository for XRayne. It contains user-facing installation documentation and scripts that install, update, or uninstall released artifacts.

## Current Contents

- `README.md`: public install, uninstall, CLI, API, update, and certificate documentation.
- `scripts/install-cli.sh`: Linux/macOS CLI installer.
- `scripts/install-cli.ps1`: Windows PowerShell CLI installer.
- `scripts/uninstall-cli.sh`: Linux/macOS CLI uninstaller.
- `scripts/uninstall-cli.ps1`: Windows PowerShell CLI uninstaller.

## Release Assets

The public README describes release assets such as:

- `xrayne-cli-linux-x64.tar.gz`
- `xrayne-cli-osx-arm64.tar.gz`
- `xrayne-cli-win-x64.zip`
- `xrayne-api-image-<version>.tar.gz`
- `xrayne-ui-image-<version>.tar.gz`

The current source of release-ready CLI artifacts is `xrayne-cli`. The API image is produced by `xrayne-panel`; the standalone UI image is produced by `xrayne-ui`. Keep this repository aligned with those release workflows instead of inventing separate build behavior here.

## Validation

For documentation-only changes, inspect rendered Markdown and verify commands stay internally consistent. For script changes, run static review first and only execute install/uninstall flows when the user explicitly asks for live validation.
