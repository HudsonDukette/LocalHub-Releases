# LocalHub Releases

Public release distribution repository for **LocalHub** (Windows x64 desktop application). Source code is maintained in a separate private repository.

## Latest Prerelease: `v0.2.0-beta.1` (Early Beta)

- **Release page**: [v0.2.0-beta.1](https://github.com/HudsonDukette/LocalHub-Releases/releases/tag/v0.2.0-beta.1)
- **Setup Zip Bundle**: [`LocalHub_0.2.0-beta.1_x64-setup.zip`](LocalHub_0.2.0-beta.1_x64-setup.zip) ([Release asset download](https://github.com/HudsonDukette/LocalHub-Releases/releases/download/v0.2.0-beta.1/LocalHub_0.2.0-beta.1_x64-setup.zip))
- **Setup Zip SHA-256**: [`LocalHub_0.2.0-beta.1_x64-setup.zip.sha256`](LocalHub_0.2.0-beta.1_x64-setup.zip.sha256) (`79441634b652df2ae118e72f058e9693897d3c0f2e45ea1629fbf8af20bfef2b`)
- **Direct NSIS Installer**: [LocalHub_0.2.0-beta.1_x64-setup.exe](https://github.com/HudsonDukette/LocalHub-Releases/releases/download/v0.2.0-beta.1/LocalHub_0.2.0-beta.1_x64-setup.exe)
- **Installer SHA-256**: [LocalHub_0.2.0-beta.1_x64-setup.exe.sha256](https://github.com/HudsonDukette/LocalHub-Releases/releases/download/v0.2.0-beta.1/LocalHub_0.2.0-beta.1_x64-setup.exe.sha256) (`802a05f869da5413444eb4c8c30f7c56120db3d4fbab76f945c44209a86da818`)

### Contents of `LocalHub_0.2.0-beta.1_x64-setup.zip`
- `LocalHub_0.2.0-beta.1_x64-setup.exe` — Windows x64 NSIS setup installer (4,175,674 bytes)
- `LocalHub_0.2.0-beta.1_x64-setup.exe.sha256` — SHA-256 checksum file for the installer
- `README.txt` — Installation instructions, system requirements, and beta release notes

### Verification & Installation Notes
1. Verify the zip or installer SHA-256 checksum in PowerShell before running:
   ```powershell
   Get-FileHash .\LocalHub_0.2.0-beta.1_x64-setup.zip -Algorithm SHA256
   Get-FileHash .\LocalHub_0.2.0-beta.1_x64-setup.exe -Algorithm SHA256
   ```
2. This early beta is an unsigned manual-install prerelease (not Authenticode-signed and no Tauri updater signature/manifest yet). Windows SmartScreen may display a warning.
3. Automatic in-app updates remain disabled until the signed updater channel is configured.
